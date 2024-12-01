# Specific Code Examples with Claude.ai

## 1. Code Analysis

### Example 1: Code Review Request
```
Review this Python code for best practices, performance optimizations, and potential security issues:

def process_user_data(input_data):
    results = {}
    try:
        for item in input_data.split(','):
            key, value = item.split('=')
            results[key.strip()] = value.strip()
    except Exception as e:
        print(f'Error: {e}')
    return results
```

### Example 2: Performance Optimization
```
Analyze this function for performance and suggest optimizations:

def find_duplicates(arr):
    duplicates = []
    for i in range(len(arr)):
        for j in range(i + 1, len(arr)):
            if arr[i] == arr[j] and arr[i] not in duplicates:
                duplicates.append(arr[i])
    return duplicates
```

## 2. Data Analysis

### Example 1: CSV Analysis
```
Analyze this sales data CSV:
- Calculate monthly trends
- Identify top-performing products
- Generate summary statistics
- Create visualization recommendations

Fields:
- date: Transaction date
- product_id: Unique product identifier
- quantity: Units sold
- price: Unit price
- customer_id: Unique customer identifier
```

### Example 2: Financial Analysis
```
Analyze this financial data and provide:
1. Key performance indicators
2. Month-over-month growth rates
3. Anomaly detection
4. Future projections

Include visualizations suggestions for:
- Revenue trends
- Expense breakdown
- Profit margins
- Growth metrics
```

## 3. Content Generation

### Example 1: Technical Documentation
```
Create API documentation for this endpoint:

Endpoint: /api/v1/users
Method: POST
Payload:
{
    "username": "string",
    "email": "string",
    "role": "string"
}

Include:
- Request/response formats
- Authentication requirements
- Error codes
- Usage examples
- Rate limiting info
```

### Example 2: Tutorial Creation
```
Create a step-by-step tutorial for implementing user authentication using JWT tokens:

Cover:
1. Basic concepts
2. Implementation steps
3. Security considerations
4. Best practices
5. Common pitfalls
6. Testing strategies
7. Code examples in Python
```

## 4. Problem Solving

### Example 1: Algorithm Design
```
Design an algorithm to solve this problem:

Given a binary tree, find the longest path between any two nodes.

Provide:
1. Problem analysis
2. Algorithm design
3. Pseudocode
4. Implementation in Python
5. Time/space complexity analysis
6. Test cases
```

### Example 2: System Design
```
Design a URL shortening service like bit.ly:

Requirements:
- Handle 100M active users
- 500M URL shortenings per month
- 99.9% availability
- Low latency

Provide:
1. Architecture diagram description
2. Component design
3. Database schema
4. API design
5. Scaling strategy
```

## 5. Code Generation

### Example 1: React Component
```
Create a React component for a data dashboard:

Features:
- Display user statistics
- Show recent activities
- Filter by date range
- Sort by different metrics
- Export data functionality

Use:
- TypeScript
- Tailwind CSS
- React Hooks
- Error handling
```

### Example 2: API Integration
```
Create a Python class to interact with a REST API:

Requirements:
- Handle authentication
- Implement CRUD operations
- Rate limiting
- Error handling
- Retry mechanism
- Async support
- Logging
```

## 6. Testing

### Example 1: Unit Tests
```
Write unit tests for this function:

def calculate_discount(price, quantity, customer_type):
    base_discount = 0
    if quantity > 10:
        base_discount += 0.1
    if customer_type == 'premium':
        base_discount += 0.05
    final_price = price * quantity * (1 - base_discount)
    return round(final_price, 2)

Include tests for:
- Edge cases
- Invalid inputs
- Boundary values
- Different discount combinations
```

### Example 2: Integration Tests
```
Create integration tests for a user registration flow:

Flow:
1. User submits registration form
2. Email verification sent
3. User verifies email
4. Profile completion

Test:
- Happy path
- Validation errors
- Duplicate emails
- Email service failures
- Database interactions
```

## 7. Debugging

### Example 1: Error Analysis
```
Debug this code that's producing unexpected results:

def merge_lists(list1, list2):
    result = []
    i = j = 0
    while i < len(list1) and j < len(list2):
        if list1[i] < list2[j]:
            result.append(list1[i])
            i += 1
        else:
            result.append(list2[j])
            j += 1
    return result

Provide:
1. Issue identification
2. Root cause analysis
3. Fix recommendation
4. Testing approach
```

### Example 2: Performance Debug
```
Analyze this slow-performing code:

def find_common_elements(list1, list2, list3):
    common = []
    for item in list1:
        if item in list2 and item in list3:
            common.append(item)
    return common

Provide:
1. Performance analysis
2. Bottleneck identification
3. Optimization suggestions
4. Benchmarking approach
```