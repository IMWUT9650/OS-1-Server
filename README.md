# Introduction
The server-side code repository for the LLM-based eyewear dialogue system OS-1.

# Directory Structure
```
├── base
│   ├── active.py
│   ├── agent.py
│   ├── auditory.py
│   ├── conversation.py
│   ├── history.py
│   ├── memorizer.py
│   ├── message.py
│   ├── parser.py
│   ├── persona.py
│   ├── prompt.py
│   ├── response.py
│   ├── tag.py
│   ├── visual.py
│   └── __init__.py
├── core
│   ├── active.py
│   ├── auditory.py
│   ├── context_memorizer.py
│   ├── conversation_memorizer.py
│   ├── history.py
│   ├── memory_evaluator.py
│   ├── message.py
│   ├── policy.py
│   ├── prompt.py
│   ├── response.py
│   ├── search.py
│   ├── visual.py
│   └── __init__.py
├── templates
│   ├── agent.py
│   ├── context.py
│   ├── conversation.py
│   ├── custom_prompt.py
│   ├── event.py
│   ├── history.py
│   ├── memory.py
│   ├── prompt.py
│   ├── response.py
│   └── __init__.py
├── tools
│   ├── nls
│   ├── ali_asr_api.py
│   ├── asr_ali_nls.py
│   ├── asr_api.py
│   ├── asr_server.py
│   ├── authorization.py
│   ├── bs64.py
│   ├── embedding_api.py
│   ├── embedding_server.py
│   ├── helper.py
│   ├── image_caption.py
│   ├── image_tool.py
│   ├── llama_api.py
│   ├── llava_api.py
│   ├── llm.py
│   ├── log.py
│   ├── memory.py
│   ├── memory_retriever.py
│   ├── milvus_client.py
│   ├── mongo.py
│   ├── openai_api.py
│   ├── redis_client.py
│   ├── similarity.py
│   ├── time_fmt.py
│   ├── tts_ali_nls.py
│   ├── tts_api.py
│   ├── tts_server.py
│   ├── user_command.py
│   └── __init__.py
├── .gitignore
├── data_server.py
├── image_server.py
├── audio_server.py
├── audio_server_v2.py
├── chatbot_server.py
├── msg_server.py
├── context_cron_task.py
├── conversation_cron_task.py
├── deploy_config.yaml
├── docker-compose.yml
├── requirements.txt
├── restart.sh
├── start.sh
├── stop.sh
└── system_monitor.py
```
