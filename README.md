# ChatGPT

A chat client for the OpenAI API: messages go out over OkHttp and come back into a two-sided RecyclerView conversation.

## Features

- RecyclerView with separate layouts for user and assistant messages
- Requests built and sent with OkHttp
- `ModelMessage` data class and `AdapterMessage` for the chat list

## Tech stack

- **Language:** Kotlin
- **UI:** XML layouts with View binding
- **SDK:** min 24, target 34
- **Package:** `com.example.chatgpt`
- **Libraries:** OkHttp

<sub>6 source files · 234 lines of code · 2 layouts</sub>

## Getting started

```bash
git clone https://github.com/rajabbov/ChatGPT.git
```

Open the folder in Android Studio, let Gradle sync, and run the `app` configuration on a device or emulator.

### Configuration

Set `OPENAI_API_KEY` in `local.properties`. The key is read through `BuildConfig` and is never committed.

## License

MIT
