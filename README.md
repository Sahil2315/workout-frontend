# AI Assisted Workout Planning App

![image](https://github.com/user-attachments/assets/28d3f1e1-91b2-4a1d-843c-3d9373307510)

## Functional Requirements:
- Create Workout Plans on the Client's Request.
- Manage Workout Plans according to Progress / Experience.
- Create Workout Prompts for DeepSeek R1.
- Convert DeepSeek R1's Response into JSON Format to be Serverd Back to the Client.
- Store User Info on the Server if User is Logged In.
- Server Sync

## Non Functional Requirements:
### Note - Deepseek R1's Free Tier usually takes about 1 - 2 Minutes to completely generate the result.
- Low Server - Client Latency
- Low Server - AI Latency
- UI Elements to Provide Ease of Use to the User - such as Manually Tracking the Current Workout
- JSON Data Conversion should be correct and predefined JSON Structure should be provided as a prompt to the GenAI (Deepseek R1)
- The Mobile App should be at least Partially Operable without Internet Connectivity (for Workout Tracking)
- The Syncing with Server Function should automatically be performed based on the Local Storage Token (JWT)
