# PTR-001 — Provider and Model Selection Record

> **PTR-001 v0.1 — GOOGLE GEMINI OPAQUE PAIRED TRIAL PREPARED — EXECUTION NOT AUTHORIZED**

## Exact observed qualification block

    PROVIDER=Google
    INTERFACE=Gemini web app
    BROWSER_INCOGNITO=True
    TEMPORARY_CHAT=True

    AVAILABLE_MODEL_LABELS=3.5 Flash-Lite, 3.5 Flash, 3.1 Pro + Extended Thinking option
    SELECTED_MODEL_LABEL=Not selected
    BACKEND_MODEL_IDENTIFIER=Not exposed

    PERSONAL_CONTEXT=False
    PAST_CHAT_MEMORY=False
    CONNECTED_APPS=False
    CUSTOM_INSTRUCTIONS=False
    GEM_OR_CUSTOM_WORKFLOW=False
    NOTEBOOK=False
    DEEP_RESEARCH=False
    CHROME_TAB_CONTEXT=False
    BROWSER_CONTROL=False
    WEB_SEARCH=<Off / not enabled / not explicitly controllable>

    FILE_UPLOAD_AVAILABLE=True
    TEMPORARY_CHAT_FILE_UPLOAD_AVAILABLE=True

    CURRENT_PLAN_LABEL=Google AI Plus (2TB)
    UPGRADE_REQUIRED_FOR_AVAILABLE_MODELS=none shown as available with upgrade
    INCREMENTAL_SPEND_USD=0
    PAID_API_OR_CREDITS_ENABLED=False
    PAID_SPILLOVER_POSSIBLE=Not exposed

    NO_CONTENT_SUBMITTED=True
    NO_FILE_UPLOADED=True

Scott observed this interface state in a fresh browser-incognito Gemini Temporary Chat before submitting or uploading content. The qualification-only chat remained empty and is not an execution chat.

## Selected configuration

    PROVIDER=Google
    INTERFACE=Gemini web app
    SELECTED_MODEL_LABEL=3.1 Pro
    EXTENDED_THINKING=True
    BACKEND_MODEL_IDENTIFIER=Not exposed
    BROWSER_INCOGNITO=True
    TEMPORARY_CHAT=True
    CURRENT_PLAN_LABEL=Google AI Plus (2TB)
    INCREMENTAL_SPEND_USD=0
    PAID_API_OR_CREDITS_ENABLED=False
    PAID_SPILLOVER_POSSIBLE=Not exposed

The strongest observed zero-upgrade reasoning configuration was selected because the formal decoding objective prioritizes reasoning depth rather than low latency. The exact same displayed model and thinking setting must be used for both opaque conditions. This is not a model-comparison design.

There is no fallback to 3.5 Flash, 3.5 Flash-Lite, another model, another interface, API access, or another provider. If the exact label or setting is unavailable, quota-limited, visibly rerouted, or requires payment or upgrade, the package remains dormant.

## Limitations and exposure

The user-observed label is not proof of backend model identity, provider isolation, retention behavior, routing, paid spillover, or future availability. Temporary Chat and incognito are context-reduction controls, not proof of zero retention, hidden-state isolation, no provider access, or no human review.

WEB_SEARCH was not explicitly controllable in the observed interface. Visible search, grounding, retrieval, citation generation, or other tool behavior must be preserved and classified as contamination. The second condition necessarily follows same-provider exposure to the first; separate prior-same-condition and prior-other-condition fields are required in any future validity record.

No purchase, upgrade, API activation, billing change, paid-credit use, submission, upload, or provider execution was authorized or performed by D-032.
