# Các Giải Pháp Thay Thế GitHub Copilot Chat Extension

**Mục đích**: Tìm kiếm các giải pháp mã nguồn mở có thể tích hợp với LLM riêng (devmate - OpenAI compatible)

**Ngày tạo**: 19/01/2026

---

## 1. VS Code Copilot Chat (Microsoft)

- **GitHub**: https://github.com/microsoft/vscode-copilot-chat
- **License**: MIT ✅
- **Ngôn ngữ**: TypeScript (96.2%)
- **Stars**: ~9.3k
- **Mô tả**: Official GitHub Copilot Chat extension cho VS Code từ Microsoft

### Tính năng chính:
- AI-powered coding sessions: Agent mode, Edit mode, Inline chat
- Ghost text suggestions và next edit suggestions (Copilot NES)
- Chat view với participants, variables và slash commands
- Inline chat để refactoring và code generation
- Multi-turn conversations
- Code actions integration
- Context-aware suggestions
- Hỗ trợ mọi ngôn ngữ lập trình

### Ưu điểm:
- MIT License ✅
- Official extension từ Microsoft với 9.3k stars
- Production-ready với 225 releases
- Active development (90+ contributors)
- Documentation chi tiết và community support
- Tích hợp sâu với VS Code
- Multi-model support

### Nhược điểm:
- Yêu cầu GitHub Copilot subscription (có free tier)
- Closed-source backend (chỉ extension là open source)
- Phụ thuộc vào GitHub/Microsoft infrastructure

---

## 2. Cline (formerly Claude Dev)

- **GitHub**: https://github.com/cline/cline
- **License**: Apache 2.0
- **Ngôn ngữ**: TypeScript (86.3%), Go (8.5%), JavaScript (3.5%)
- **Stars**: ~57k
- **Mô tả**: Autonomous coding agent trong VS Code với khả năng create/edit files, execute commands, use browser

### Tính năng chính:
- **Use any API and Model**: OpenRouter, Anthropic, OpenAI, Google Gemini, AWS Bedrock, Azure, GCP Vertex, Cerebras, Groq, LM Studio/Ollama
- **Run commands in terminal**: Execute commands với shell integration
- **Create and Edit Files**: Diff view với linter/compiler error monitoring
- **Use the Browser**: Computer Use capability với screenshot và console logs
- **Model Context Protocol (MCP)**: Tạo custom tools
- **Add Context**: @url, @problems, @file, @folder
- **Checkpoints**: Compare và restore workspace snapshots
- Token usage tracking chi tiết

### Ưu điểm:
- Cộng đồng cực lớn (57k stars, 281 contributors)
- 215 releases - very active
- Rất mạnh cho complex tasks
- UI/UX xuất sắc với approval workflow
- Enterprise version available
- Hỗ trợ nhiều LLM providers kể cả OpenAI-compatible

### Nhược điểm:
- Apache 2.0 license (không phải MIT)
- Yêu cầu careful monitoring vì có quyền execute commands
- Token usage có thể cao cho large tasks

---

## 3. Continue.dev

- **GitHub**: https://github.com/continuedev/continue
- **License**: Apache 2.0
- **Ngôn ngữ**: TypeScript (83.8%), JavaScript (7.8%), Kotlin (4.0%)
- **Stars**: ~30.9k
- **Mô tả**: Open-source AI coding assistant với Cloud Agents, CLI Agents và IDE Agents

### Tính năng chính:
- **Cloud Agents**: Workflows tự động chạy trên PR opens, schedules, events
- **CLI Agents**: Terminal mode (TUI) với real-time execution
- **IDE Agents**: VS Code và JetBrains integration
- Hỗ trợ OpenAI-compatible APIs
- Chat với context awareness
- Code completion và autocomplete
- Background agents cho continuous AI
- Mission Control hub để quản lý agents
- Multi-model support (GPT, Claude, Gemini, Qwen, etc.)

### Ưu điểm:
- Cộng đồng rất lớn (30.9k stars, 440+ contributors)
- 763 releases - very active development
- Documentation đầy đủ
- Dễ dàng tích hợp với custom LLM endpoints
- Support cả cloud và self-hosted
- CLI mode mạnh mẽ

### Nhược điểm:
- License Apache 2.0 (không phải MIT)
- Complexity cao hơn các solution đơn giản

---

## 4. Tabby

- **GitHub**: https://github.com/TabbyML/tabby
- **License**: Apache 2.0 + Enterprise Edition
- **Ngôn ngữ**: Rust (92.9%), Python (4.5%)
- **Stars**: ~32.8k
- **Mô tả**: Self-hosted AI coding assistant, open-source alternative to GitHub Copilot

### Tính năng chính:
- Self-contained, không cần DBMS hay cloud service
- OpenAPI interface, dễ tích hợp
- Support consumer-grade GPUs
- Code completion và chat interface
- Web UI để quản lý models và users
- Support cho nhiều IDE (VS Code, JetBrains, Vim, Neovim)
- Model registry và deployment
- RAG (Retrieval Augmented Generation)
- GitLab Merge Request context indexing
- REST APIs để enhance với custom documentation
- Docker deployment với CUDA/ROCm support

### Ưu điểm:
- Cộng đồng lớn (32.8k stars, 128 contributors)
- 246 releases - mature product
- Security và privacy cao (self-hosted)
- Enterprise-ready với authentication
- Performance tốt (Rust backend)
- Live demo available
- Có thể chạy on-premise

### Nhược điểm:
- License Apache 2.0 (không phải MIT)
- Setup phức tạp hơn các cloud solutions
- Cần infrastructure để host

---

## 5. Roo Code

- **GitHub**: https://github.com/RooCodeInc/Roo-Code
- **License**: Apache 2.0
- **Ngôn ngữ**: TypeScript (98.7%)
- **Stars**: ~21.8k
- **Mô tả**: AI-Powered Dev Team trong VS Code với multiple specialized modes

### Tính năng chính:
- **Multiple Modes**: Code, Architect, Ask, Debug, và Custom Modes
- **Code Mode**: Everyday coding, edits, và file operations
- **Architect Mode**: Plan systems, specs, migrations
- **Ask Mode**: Fast answers, explanations, docs
- **Debug Mode**: Trace issues, add logs, isolate root causes
- **Custom Modes**: Build specialized modes cho team/workflow
- **Roomote Control**: Remote control tasks trong local VS Code
- **MCP Servers**: Model Context Protocol support
- **Codebase Indexing**: Context management
- **Checkpoints**: Save và restore workflow states

### Ưu điểm:
- Cộng đồng lớn (21.8k stars, 285 contributors)
- 230 releases - very active development
- Multiple specialized modes cho different workflows
- Roomote Control cho remote task management
- Documentation đầy đủ với video tutorials
- Strong community (Discord, Reddit, YouTube)
- Hỗ trợ OpenAI-compatible APIs

### Nhược điểm:
- Apache 2.0 license (không phải MIT)
- Complexity cao với nhiều modes
- Yêu cầu learning curve để tận dụng hết features

---

## 6. Cody (Sourcegraph)

- **GitHub**: https://github.com/sourcegraph/cody-public-snapshot
- **License**: Apache 2.0
- **Ngôn ngữ**: TypeScript
- **Stars**: ~2k+
- **Mô tả**: AI coding assistant từ Sourcegraph với code intelligence

### Tính năng chính:
- VS Code, JetBrains, Neovim extensions
- Hỗ trợ nhiều LLM backends
- Code search và semantic understanding
- Chat với code context
- Có thể self-host Sourcegraph instance
- Enterprise features

### Ưu điểm:
- Tích hợp code search mạnh mẽ
- Codebase understanding tốt
- Enterprise support

### Nhược điểm:
- Yêu cầu Sourcegraph infrastructure để tận dụng hết tính năng
- Phức tạp hơn các giải pháp khác

---

## 7. ChatIDE

- **GitHub**: https://github.com/yagil/ChatIDE
- **License**: MIT ✅
- **Ngôn ngữ**: TypeScript (66.7%), JavaScript (22.1%)
- **Stars**: 223
- **Mô tả**: Minimal AI coding assistant VS Code extension - ChatGPT và Claude trong IDE

### Tính năng chính:
- Simple chat interface trong VS Code
- Hỗ trợ OpenAI ChatGPT (gpt-4, gpt-4-0613, gpt-3.5-turbo, gpt-3.5-turbo-16k)
- Hỗ trợ Anthropic Claude (claude-v1.3)
- Bring Your Own API keys
- Code selection context
- Configurable model, max_tokens, temperature
- Custom system prompts
- API keys stored in VS Code secretStorage

### Ưu điểm:
- MIT License ✅
- Rất đơn giản, dễ hiểu code (2 contributors)
- Lightweight, không bloat
- Dễ fork và customize
- Tốt cho learning hoặc base project
- Hỗ trợ cả OpenAI và Anthropic

### Nhược điểm:
- Project nhỏ, 2 contributors
- Last update 2 năm trước (86 commits)
- Limited features so với Continue.dev hay Cline
- Không có code completion
- Documentation hạn chế
- Không active maintenance (No releases published)
- Known issues: không thể stop generation, closing pane khi generating gây lỗi

---

## 8. Fauxpilot

- **GitHub**: https://github.com/fauxpilot/fauxpilot
- **License**: MIT ✅
- **Ngôn ngữ**: Python
- **Stars**: ~14k+
- **Mô tả**: Locally hosted alternative to GitHub Copilot server

### Tính năng chính:
- Chạy hoàn toàn local
- Tương thích với GitHub Copilot client
- Có thể sử dụng custom models (Salesforce CodeGen, etc.)
- Docker-based deployment

### Ưu điểm:
- MIT License ✅
- Tương thích trực tiếp với Copilot client
- Dễ deploy với Docker

### Nhược điểm:
- Ít tính năng hơn các solution khác
- Community nhỏ hơn
- Update không thường xuyên

---

## 9. CodeGPT

- **GitHub**: https://github.com/carlrobertoh/CodeGPT
- **License**: Apache 2.0
- **Ngôn ngữ**: Java, Kotlin
- **Stars**: ~800+
- **Mô tả**: JetBrains và VS Code plugin cho AI assistants

### Tính năng chính:
- Hỗ trợ custom OpenAI endpoints
- Chat interface trong IDE
- Code generation và explanation
- Multiple LLM providers support
- Custom prompts

### Ưu điểm:
- Đơn giản, dễ sử dụng
- Hỗ trợ nhiều providers
- Active development

### Nhược điểm:
- JetBrains focus (VS Code support limited)
- Features ít hơn Continue.dev

---

## 10. Twinny

- **GitHub**: https://github.com/twinnydotdev/twinny
- **License**: MIT ✅
- **Ngôn ngữ**: TypeScript
- **Stars**: ~3k+
- **Mô tả**: Free and private AI extension cho VS Code

### Tính năng chính:
- Hoàn toàn miễn phí và open source
- Hỗ trợ OpenAI-compatible APIs (Ollama, LM Studio, etc.)
- Chat và code completion
- Fill-in-middle (FIM) code completion
- Privacy-focused, không thu thập data
- Lightweight và fast

### Ưu điểm:
- MIT License ✅
- Đơn giản, dễ setup
- Privacy-first
- Hoàn toàn free

### Nhược điểm:
- Community nhỏ hơn Continue.dev
- Ít features nâng cao

---

## 11. Privy

- **GitHub**: https://github.com/srikanth235/privy
- **License**: MIT ✅
- **Ngôn ngữ**: TypeScript
- **Stars**: ~100+
- **Mô tả**: Privacy-first code assistant for VS Code

### Tính năng chính:
- Local-first approach
- Custom LLM support
- VS Code extension
- Simple chat interface

### Ưu điểm:
- MIT License ✅
- Privacy focused

### Nhược điểm:
- Project nhỏ, ít contributors
- Limited features
- Documentation hạn chế

---

## 12. Open Interpreter

- **GitHub**: https://github.com/OpenInterpreter/open-interpreter
- **License**: MIT ✅
- **Ngôn ngữ**: Python
- **Stars**: ~50k+
- **Mô tả**: Natural language interface cho computer tasks

### Tính năng chính:
- Chạy code trong terminal/environment
- Hỗ trợ nhiều LLM providers
- Tương tác qua chat interface
- Execute code, create files, analyze data
- VS Code extension available

### Ưu điểm:
- MIT License ✅
- Rất mạnh mẽ, có thể thực thi code
- Community lớn
- Versatile

### Nhược điểm:
- Không focus vào IDE integration
- Có thể overkill cho simple code assistance

---

## 13. Aider

- **GitHub**: https://github.com/paul-gauthier/aider
- **License**: Apache 2.0
- **Ngôn ngữ**: Python
- **Stars**: ~12k+
- **Mô tả**: AI pair programming trong terminal

### Tính năng chính:
- Chat-based coding trong terminal
- Git integration tự động
- Hỗ trợ OpenAI-compatible endpoints
- Command-line tool
- Intelligent code editing
- Multiple file editing

### Ưu điểm:
- Rất mạnh trong việc edit code
- Git-aware
- Terminal-based, linh hoạt

### Nhược điểm:
- Không phải IDE extension native
- Terminal-focused workflow

---

## 14. Refact.ai

- **GitHub**: https://github.com/smallcloudai/refact
- **License**: BSD-3-Clause
- **Ngôn ngữ**: Rust, Python, TypeScript
- **Stars**: ~1.6k+
- **Mô tả**: Self-hosted AI coding assistant với enterprise features

### Tính năng chính:
- VS Code và JetBrains plugins
- Self-hosted server
- Code completion và chat
- Custom model support
- RAG for code context
- Telemetry và analytics

### Ưu điểm:
- Self-hosted option
- Performance tốt
- Enterprise features

### Nhược điểm:
- BSD license (không phải MIT/Apache)
- Setup phức tạp hơn

---

## 15. GPT Engineer

- **GitHub**: https://github.com/gpt-engineer-org/gpt-engineer
- **License**: MIT ✅
- **Ngôn ngữ**: Python
- **Stars**: ~51k+
- **Mô tả**: AI agent tạo entire codebase từ prompts

### Tính năng chính:
- Project generation từ natural language
- Iterative development
- Custom LLM support
- File system awareness
- Multiple project types

### Ưu điểm:
- MIT License ✅
- Community rất lớn
- Powerful cho project generation

### Nhược điểm:
- Không phải IDE extension
- Focus vào project creation hơn là day-to-day coding

---

## 16. LocalAI

- **GitHub**: https://github.com/mudler/LocalAI
- **License**: MIT ✅
- **Ngôn ngữ**: Go
- **Stars**: ~20k+
- **Mô tả**: Drop-in replacement REST API compatible với OpenAI

### Tính năng chính:
- OpenAI-compatible API
- Self-hosted
- Hỗ trợ nhiều model formats (GGUF, GGML, etc.)
- Text generation, embeddings, audio, images
- Có thể kết hợp với các IDE extensions khác

### Ưu điểm:
- MIT License ✅
- Rất linh hoạt
- Infrastructure layer tốt
- Nhiều model support

### Nhược điểm:
- Không phải IDE extension (cần combine với tools khác)
- Setup infrastructure

---

## 17. Ollama + IDE Extensions

### Ollama
- **GitHub**: https://github.com/ollama/ollama
- **License**: MIT ✅
- **Stars**: ~70k+
- **Mô tả**: Local LLM runner, dễ sử dụng

### Extensions:
- **ollama-vscode**: VS Code extension
- **Continue.dev**: Có thể dùng Ollama backend
- **Twinny**: Hỗ trợ Ollama

### Tính năng chính:
- Chạy models locally (Llama, CodeLlama, Mistral, etc.)
- OpenAI-compatible API
- Nhiều IDE integrations
- Rất đơn giản để setup

### Ưu điểm:
- MIT License ✅
- Cộng đồng rất lớn
- Dễ sử dụng nhất
- Performance tốt

### Nhược điểm:
- Cần combine với IDE extensions
- Chạy local (không phải remote LLM như devmate)

---

## 18. CodeCompanion.nvim

- **GitHub**: https://github.com/olimorris/codecompanion.nvim
- **License**: MIT ✅
- **Ngôn ngữ**: Lua
- **Stars**: ~500+
- **Mô tả**: Neovim plugin cho AI coding assistant

### Tính năng chính:
- Chat interface trong Neovim
- Custom LLM providers
- Code actions và refactoring
- Buffer-aware context
- Slash commands

### Ưu điểm:
- MIT License ✅
- Native Neovim integration

### Nhược điểm:
- Chỉ cho Neovim users
- Niche audience

---

## 19. Avante.nvim

- **GitHub**: https://github.com/yetone/avante.nvim
- **License**: Apache 2.0
- **Ngôn ngữ**: Lua
- **Stars**: ~4k+
- **Mô tả**: Cursor-like experience trong Neovim

### Tính năng chính:
- Chat UI trong Neovim giống Cursor
- Multiple providers support
- Code editing suggestions inline
- Diff view cho changes

### Ưu điểm:
- UI/UX tốt cho Neovim
- Active development

### Nhược điểm:
- Chỉ cho Neovim
- Apache license

---
