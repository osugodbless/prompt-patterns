# Objective: Extract structured data from unstructured input.

**Prompt 1:**
```
Extract the following fields from the text: Name, Age, Location, Occupation. Return the output in JSON format. John Doe, age 29, lives in Paris and works as a software engineer.
```

**Response 1:**
```
{
  "Name": "John Doe",
  "Age": 29,
  "Location": "Paris",
  "Occupation": "Software engineer"
}
```

**Prompt 2:**
```
Extract the following fields from the text: Name, Age, Location, Occupation. Return the output in JSON format. Mary Jane, age 27, lives in Nigeria and works as a Financial Analyst.
```
**Response 2:**
```
{
  "Name": "Mary Jane",
  "Age": 27,
  "Location": "Nigeria",
  "Occupation": "Financial Analyst"
}

```