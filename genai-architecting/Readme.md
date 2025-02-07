## Functional Requirements

The customer wants investment in their own AI infrastructure to ensure requirements around privacy of data, usage, and cost. This also allows them to be more compliant with government regulations and widens their target market.

It is expected that public GenAI cost will be substantial, so they've requested that models be run on an AI PC that will be run on-prem with the following characteristics:
- 10-15k USD for capital expenditure
- Serve 300 active students located in Nagasaki

## Assumptions

1. Open-source LLMs we integrate with will be powerful enough to run on hardware with an investment of 10-15k USD.
2. A single server will be connected to the internet, and it's expected this will provide enough bandwidth to serve 300 students effectively.

## Data Strategy

There is a concern relating to copyrighted materials, it's expected that we'll purchase materials for the vector database to limit system access to potentially copyrighted material.

## Considerations

Usage of IBM Granite since it's completely open source with traceable training data. This should mitigate some of the copyright concerns.

[Learn more about IBM Granite](https://huggingface.com/ibm-granite)
