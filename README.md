# LangGraph_Agentic_workflow

## 🚀 Features

### ✅ Part 1: Basic Reasoning Agent

- Stateless response from LLM  
- No tool or memory  
- Uses `StateGraph` and simple `call_model` function

### ✅ Part 2: Agent with Tool Use

- Uses LangChain `@tool` decorator  
- `ToolNode` executes registered tools  
- Conditional routing based on LLM tool call detection

### ✅ Part 3: Conversational Memory

- Uses LangGraph `MemorySaver`  
- Remembers past questions/answers  
- Answers questions like:  
  _"Which city had 25 degrees?"_
