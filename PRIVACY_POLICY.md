# Chika Privacy Policy — Publication Draft

Effective date: July 20, 2026
Publisher: Meng Yang  
Contact: mengyang0529@gmail.com

> Have the final text reviewed for the publisher's
> jurisdiction before publishing it at the App Store Connect Privacy Policy URL.

## English

Chika is an offline-first Japanese learning app. Chika does not require a Chika account and does
not include advertising, analytics, or cross-app tracking.

### Information stored on your device

Vocabulary, review activity, chat history, examples, and preferences are stored in Chika's local
SQLite database on your iPhone. API keys you choose to save are isolated by provider in the iOS
Keychain and are not exposed to Chika's web interface. You can delete conversations, vocabulary,
and a selected provider's saved API key from within Chika. Because iOS may retain Keychain items
after an app is removed, delete saved keys inside Chika before uninstalling if you do not want
them retained.

### AI features and international data transfer

AI features are optional. Before the first AI request, Chika explains the data transfer and asks
for your consent. When you choose AI chat or vocabulary enrichment, the text you submit and the
selected provider's API key are sent directly from your device to its configured API address so
that the provider can generate a response. Chika includes DeepSeek and OpenAI presets and permits
a user-configured OpenAI-compatible HTTPS endpoint. Chika does not operate an intermediary server
for these requests.

AI responses may be inaccurate or incomplete and are provided for reference only. They are not
medical, legal, financial, or other professional advice.

DeepSeek is an independent service. Under DeepSeek's published privacy practices, prompts and
related information may be processed and retained, including on servers in the People's Republic
of China. Do not submit sensitive personal information. DeepSeek's handling of the request is
governed by the DeepSeek account associated with your API key and its own terms and privacy policy:

- <https://cdn.deepseek.com/policies/en-US/deepseek-privacy-policy.html>
- <https://cdn.deepseek.com/policies/en-US/deepseek-open-platform-terms-of-service.html>

OpenAI is an independent service. OpenAI states that API inputs and outputs are not used to train
its models by default unless the API customer opts in. OpenAI may retain API abuse-monitoring logs,
which can include prompts and responses, for up to 30 days by default. OpenAI's handling of a
request is governed by the OpenAI account associated with the API key and its applicable terms and
data controls:

- <https://openai.com/policies/services-agreement/>
- <https://platform.openai.com/docs/models/default-usage-policies-by-endpoint>

For a custom endpoint, the user is responsible for verifying its operator. That operator's terms,
privacy policy, processing locations, and retention practices apply. Do not submit sensitive
personal information to any AI provider.

### Camera and photos

Camera and photo-library access is optional and is used only when you choose image recognition.
Chika performs OCR on the device. Chika does not send the selected image to an AI provider. iOS
controls the permission and you can change it in iOS Settings.

### Tracking, advertising, and sale of data

Chika does not include advertising or analytics SDKs, does not track you across apps or websites,
and does not sell personal data.

### Retention and deletion

On-device learning data remains until you delete it or remove the app. Each saved provider API key
can be deleted from Chika Settings. Requests to access or delete data held by an AI provider must
be made under the account and procedures associated with that provider and API key.

### Children

The publisher does not knowingly collect personal information from children through Chika.
Parents and guardians should supervise use of optional third-party AI features and should not let
children submit personal information to any AI provider.

### Changes and contact

Material changes will be reflected by updating this policy's effective date. Questions about
Chika can be sent to mengyang0529@gmail.com.
