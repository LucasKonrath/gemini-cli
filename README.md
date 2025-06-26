### Testing gemini-cli

## First prompt:

![alt text](image.png)

## Second prompt:

![alt text](image-1.png)

## Gemini API Free Tier Limits

The Google Gemini API offers a free tier with specific limits on requests and context windows, which vary by model.

### Request Limits:

Request limits are in place to regulate the number of calls you can make to the API in a given time and vary by model.

*   **Gemini 1.5 Flash:** This model has a higher free-tier limit of 15 requests per minute (RPM) and 1,500 requests per day (RPD).
*   **Gemini 1.5 Pro:** The free tier for this model is more limited, at 2 requests per minute (RPM) and 50 requests per day (RPD).
*   **Gemini 2.5 Pro Experimental:** Within Google AI Studio, the documented rate limits are 5 RPM and 25 RPD.

It's important to note that rate limits are applied per project, not per API key. Exceeding any of these limits will result in a rate limit error.

### Context Window:

The context window refers to the amount of text the model can consider at one time.

*   Several Gemini models, including Gemini 1.5 Flash and Gemini 2.0 Flash, offer a 1 million token context window.
*   Gemini 2.5 Pro boasts an even larger 2 million token context window.

While the free tier provides access to these large context windows, there can be limitations. For instance, the full 2 million token context of Gemini 2.5 Pro may not always be available in the free tier. Users on the free tier may also encounter tokens-per-minute (TPM) limits, which can make it challenging to utilize the full context window without hitting an API error. For example, Gemini 1.5 Flash has a free tier limit of 32,000 tokens per minute (TPM).

### Google AI Studio:

Google AI Studio provides a way to test and use Gemini models for free. Usage of Google AI Studio itself is free of charge in all available countries, regardless of whether you have set up a billing account. This allows you to experiment with models and even fine-tune them at no cost.

For users who require higher rate limits or more extensive use of the context window, there is a pay-as-you-go plan available.