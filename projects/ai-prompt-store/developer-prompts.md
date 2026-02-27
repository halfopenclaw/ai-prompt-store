# 💻 Developer Prompts Pack

## 1. Code Review Assistant

```
Perform a code review for the following [語言] code:

[貼上代碼]

Please analyze:
1. Security issues
2. Performance problems
3. Code smells
4. Best practices violations
5. Suggestions for improvement

Format as a structured report with severity levels.
```

## 2. Bug Hunter

```
I have a [語言] application with this error:

Error: [錯誤信息]
Context: [相關代碼/環境]

Please:
1. Identify possible causes
2. Suggest debugging steps
3. Provide fix options
4. Recommend prevention measures
```

## 3. API Documentation Writer

```
Generate API documentation for:

Endpoint: [API endpoint]
Method: [GET/POST/etc]
Purpose: [用途]

Please document:
1. Description
2. Parameters (required/optional)
3. Request format
4. Response format
5. Error codes
6. Example requests/responses

Output in [OpenAPI/Markdown/Postman] format.
```

## 4. Unit Test Generator

```
Generate unit tests for this [語言] function:

[貼上函數]

Requirements:
- Use [測試框架]
- Cover edge cases
- Include mock data
- Follow best practices
- Achieve >80% coverage

Provide complete test file.
```

## 5. Database Schema Designer

```
Design a database schema for [應用類型]。

Requirements:
- Support [功能列表]
- Handle [數據量]
- Include [特殊需求]

Please provide:
1. ER Diagram description
2. Table structures
3. Relationships
4. Indexes
5. Migration scripts

Use [SQL/NoSQL] and explain choices.
```

## 6. Architecture Review

```
Review the architecture for [系統描述]。

Please evaluate:
1. Scalability
2. Security
3. Maintainability
4. Performance
5. Cost efficiency

Provide:
- Current weaknesses
- Improvement suggestions
- Recommended patterns
- Tech stack alternatives
```
