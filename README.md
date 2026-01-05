# ElevenLabs Translator

Express app with ElevenLabs agent for real-time translation using voice conversations.

## Setup

1. Install dependencies:
```bash
npm install
```

2. Copy `.env.example` to `.env` and fill in your credentials:
```bash
cp .env.example .env
```

3. Add your ElevenLabs API key and Agent IDs to `.env`:
```
ELEVENLABS_API_KEY=your_api_key_here
AGENT_ID=your_agent_id_here
AGENT_ID2=your_agent_id2_here
```

Note: `AGENT_ID` is used for "My Voice" option, `AGENT_ID2` is used for "Predefined Voice" option.

## Running

Start the server:
```bash
npm start
```

For development with auto-reload:
```bash
npm run dev
```

The app will be available at `http://localhost:3000`

## Features

- Multi-language support (English, Armenian, Chinese, Spanish)
- Real-time voice translation
- Dynamic prompts based on selected language
- Modern, responsive UI

## Usage

1. Select your target language from the dropdown
2. Click "Start Talking"
3. Grant microphone permissions when prompted
4. Start speaking - the AI will translate and respond in the selected language
