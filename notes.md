# GA4 Agents Workshop Setup Instructions

Welcome to the GA4 Agents workshop! Follow the steps below to get your environment set up and ready to run.

## 1. Authenticate Google Cloud

First, authenticate with Google Cloud to get your required access token.

```bash
gcloud auth application-default login
gcloud auth application-default print-access-token
```

## 2. Upload GA4 Agent to Langflow

To proceed, you'll need to upload the `GA4 Agent.json` file to Langflow. Without this, the agents won’t work properly.
You can either:

- Duplicate the Langflow space: [Langflow GA4 Agent](https://huggingface.co/spaces/Sitewiz/Langflow)

- Upload the JSON to your own instance of Langflow

## 3. Set Up API Keys

Ensure you set up both the `openai_api_key` and `bigquery_Api_key`. These can be obtained by running:

```bash
gcloud auth application-default login
gcloud auth application-default print-access-token
```

## 4. Explore the Agent Flows

Each Analyst Agent represents a large language model (LLM) that processes instructions, creates, and runs SQL queries on BigQuery. The model will understand and process the output and even suggest queries to run next.

Feel free to experiment with the prompts, edit the agents, and add more by:

- Ungrouping an agent

- Making your changes

- Regrouping the agent

## 5. Run on Your Own BigQuery Dataset

You can also run the agents on your own BigQuery dataset instead of the public eCommerce one, enabling you to automate insights from your Google Analytics.

## Useful Links

- [Langflow Workspace](https://huggingface.co/spaces/Sitewiz/Langflow)

- [MeasureCamp Chicago](https://chicago.measurecamp.org/)

- [LinkedIn Group](https://www.linkedin.com/groups/13001103/)

- [Workshop Documentation](https://docs.google.com/document/d/13J8YPuMP8UUJYYa3S19j7S4WBRQUlny5-TaMUICJqQs/edit)

- [Langflow Flow Reference](https://astra.datastax.com/langflow/2305abbf-2e85-43bc-a1b5-8752a048f082/flow/31c412ed-7515-47f6-8a2a-b80741a17c4a)
