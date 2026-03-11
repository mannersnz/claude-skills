# Skill: API Connector

## Purpose
Help connect to APIs and build integrations. Takes an API description or documentation and creates working code to fetch, send, and process data.

## Instructions
When asked to connect to an API:

1. **Understand the integration:**
   - What API are we connecting to?
   - What data do we need to get or send?
   - What authentication is required (API key, OAuth, bearer token)?
   - What should happen with the response?

2. **Build the connection:**
   - Write clean, working code for the API call
   - Handle authentication properly (never hardcode keys — use environment variables)
   - Parse the response and extract useful data
   - Handle errors gracefully (network failures, rate limits, bad responses)

3. **Code standards:**
   - Use `fetch` for JavaScript/TypeScript
   - Use `requests` for Python
   - Include error handling for every API call
   - Add comments explaining each step
   - Use environment variables for all secrets: `process.env.API_KEY`

4. **Deliver:**
   - Working code with example usage
   - List of environment variables needed
   - Example of the API response format
   - Common gotchas for that specific API

## Output Format
```javascript
// Environment variables needed:
// API_KEY=your_api_key_here

async function fetchData() {
  // Clear, commented, working code
}
```

## Common APIs This Handles
- Xero (accounting)
- Google Sheets / Drive
- Resend / SendGrid (email)
- Stripe (payments)
- OpenAI / Claude (AI)
- Facebook / Instagram (social)
- Shopify (e-commerce)
- Any REST API with documentation
