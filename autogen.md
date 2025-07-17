├── .azure
    └── pipelines
    │   ├── build.yaml
    │   └── templates
    │       ├── build.yaml
    │       └── vars.yaml
├── .devcontainer
    ├── Dockerfile
    ├── devcontainer.json
    ├── docker-compose.yml
    └── startup.sh
├── .gitattributes
├── .github
    ├── ISSUE_TEMPLATE
    │   ├── 1-bug_report.yml
    │   ├── 2-doc_issue.yml
    │   ├── 3-maintainer_only.yml
    │   └── config.yml
    ├── PULL_REQUEST_TEMPLATE.md
    └── workflows
    │   ├── checks.yml
    │   ├── codeql.yml
    │   ├── docs.yml
    │   ├── dotnet-build.yml
    │   ├── dotnet-release.yml
    │   ├── integration.yml
    │   ├── issue-user-responded.yml
    │   ├── lfs-check.yml
    │   ├── pytest-mem0.yml
    │   ├── python-package-0.2.yml
    │   └── single-python-package.yml
├── .gitignore
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── FAQ.md
├── LICENSE
├── LICENSE-CODE
├── README.md
├── SECURITY.md
├── SUPPORT.md
├── TRANSPARENCY_FAQS.md
├── autogen-landing.jpg
├── codecov.yml
├── docs
    ├── design
    │   ├── 01 - Programming Model.md
    │   ├── 02 - Topics.md
    │   ├── 03 - Agent Worker Protocol.md
    │   ├── 04 - Agent and Topic ID Specs.md
    │   ├── 05 - Services.md
    │   └── readme.md
    ├── dotnet
    │   ├── .gitignore
    │   ├── README.md
    │   ├── core
    │   │   ├── differences-from-python.md
    │   │   ├── index.md
    │   │   ├── installation.md
    │   │   ├── protobuf-message-types.md
    │   │   ├── toc.yml
    │   │   └── tutorial.md
    │   ├── docfx.json
    │   ├── images
    │   │   ├── favicon.ico
    │   │   └── logo.svg
    │   ├── index.md
    │   ├── template
    │   │   └── public
    │   │   │   ├── main.css
    │   │   │   └── main.js
    │   └── toc.yml
    └── switcher.json
├── dotnet
    ├── .config
    │   └── dotnet-tools.json
    ├── .editorconfig
    ├── .gitattributes
    ├── .gitignore
    ├── .tools
    │   ├── run_all_notebook.ps1
    │   └── test-aot-compatibility.ps1
    ├── AutoGen.sln
    ├── AutoGen.v3.ncrunchsolution
    ├── Directory.Build.props
    ├── Directory.Build.targets
    ├── Directory.Packages.props
    ├── NuGet.config
    ├── PACKAGING.md
    ├── README.md
    ├── eng
    │   ├── MetaInfo.props
    │   ├── Sign.props
    │   └── opensource.snk
    ├── global.json
    ├── nuget
    │   ├── NUGET.md
    │   ├── README.md
    │   ├── icon.png
    │   └── nuget-package.props
    ├── resource
    │   └── images
    │   │   ├── background.png
    │   │   └── square.png
    ├── samples
    │   ├── AgentChat
    │   │   ├── AutoGen.Anthropic.Sample
    │   │   │   ├── Anthropic_Agent_With_Prompt_Caching.cs
    │   │   │   ├── AutoGen.Anthropic.Sample.csproj
    │   │   │   ├── Create_Anthropic_Agent.cs
    │   │   │   ├── Create_Anthropic_Agent_With_Tool.cs
    │   │   │   └── Program.cs
    │   │   ├── AutoGen.Basic.Sample
    │   │   │   ├── AutoGen.Basic.Sample.csproj
    │   │   │   ├── CodeSnippet
    │   │   │   │   ├── AgentCodeSnippet.cs
    │   │   │   │   ├── BuildInMessageCodeSnippet.cs
    │   │   │   │   ├── CreateAnAgent.cs
    │   │   │   │   ├── FunctionCallCodeSnippet.cs
    │   │   │   │   ├── GetStartCodeSnippet.cs
    │   │   │   │   ├── MiddlewareAgentCodeSnippet.cs
    │   │   │   │   ├── MistralAICodeSnippet.cs
    │   │   │   │   ├── OpenAICodeSnippet.cs
    │   │   │   │   ├── PrintMessageMiddlewareCodeSnippet.cs
    │   │   │   │   ├── RunCodeSnippetCodeSnippet.cs
    │   │   │   │   ├── SemanticKernelCodeSnippet.cs
    │   │   │   │   ├── TypeSafeFunctionCallCodeSnippet.cs
    │   │   │   │   └── UserProxyAgentCodeSnippet.cs
    │   │   │   ├── Example01_AssistantAgent.cs
    │   │   │   ├── Example02_TwoAgent_MathChat.cs
    │   │   │   ├── Example03_Agent_FunctionCall.cs
    │   │   │   ├── Example04_Dynamic_GroupChat_Coding_Task.cs
    │   │   │   ├── Example05_Dalle_And_GPT4V.cs
    │   │   │   ├── Example06_UserProxyAgent.cs
    │   │   │   ├── Example07_Dynamic_GroupChat_Calculate_Fibonacci.cs
    │   │   │   ├── Example08_LMStudio.cs
    │   │   │   ├── Example10_SemanticKernel.cs
    │   │   │   ├── Example11_Sequential_GroupChat_Example.cs
    │   │   │   ├── Example12_TwoAgent_Fill_Application.cs
    │   │   │   ├── Example13_OpenAIAgent_JsonMode.cs
    │   │   │   ├── Example14_MistralClientAgent_TokenCount.cs
    │   │   │   ├── Example15_GPT4V_BinaryDataImageMessage.cs
    │   │   │   ├── Example16_OpenAIChatAgent_ConnectToThirdPartyBackend.cs
    │   │   │   ├── Example17_ReActAgent.cs
    │   │   │   ├── GettingStart
    │   │   │   │   ├── Agent_Middleware.cs
    │   │   │   │   ├── Chat_With_Agent.cs
    │   │   │   │   ├── Dynamic_Group_Chat.cs
    │   │   │   │   ├── FSM_Group_Chat.cs
    │   │   │   │   ├── Image_Chat_With_Agent.cs
    │   │   │   │   ├── Streaming_Tool_Call.cs
    │   │   │   │   └── Use_Tools_With_Agent.cs
    │   │   │   ├── GlobalUsing.cs
    │   │   │   ├── LLMConfiguration.cs
    │   │   │   └── Program.cs
    │   │   ├── AutoGen.Gemini.Sample
    │   │   │   ├── AutoGen.Gemini.Sample.csproj
    │   │   │   ├── Chat_With_Google_Gemini.cs
    │   │   │   ├── Chat_With_Vertex_Gemini.cs
    │   │   │   ├── Function_Call_With_Gemini.cs
    │   │   │   ├── Image_Chat_With_Vertex_Gemini.cs
    │   │   │   └── Program.cs
    │   │   ├── AutoGen.Ollama.Sample
    │   │   │   ├── AutoGen.Ollama.Sample.csproj
    │   │   │   ├── Chat_With_LLaMA.cs
    │   │   │   ├── Chat_With_LLaVA.cs
    │   │   │   └── Program.cs
    │   │   ├── AutoGen.OpenAI.Sample
    │   │   │   ├── AutoGen.OpenAI.Sample.csproj
    │   │   │   ├── Connect_To_Azure_OpenAI.cs
    │   │   │   ├── Connect_To_Ollama.cs
    │   │   │   ├── Connect_To_OpenAI_o1_preview.cs
    │   │   │   ├── Program.cs
    │   │   │   ├── Structural_Output.cs
    │   │   │   ├── Tool_Call_With_Ollama_And_LiteLLM.cs
    │   │   │   └── Use_Json_Mode.cs
    │   │   ├── AutoGen.SemanticKernel.Sample
    │   │   │   ├── AutoGen.SemanticKernel.Sample.csproj
    │   │   │   ├── Create_Semantic_Kernel_Agent.cs
    │   │   │   ├── Create_Semantic_Kernel_Chat_Agent.cs
    │   │   │   ├── Program.cs
    │   │   │   ├── Use_Bing_Search_With_Semantic_Kernel_Agent.cs
    │   │   │   └── Use_Kernel_Functions_With_Other_Agent.cs
    │   │   └── AutoGen.WebAPI.Sample
    │   │   │   ├── AutoGen.WebAPI.Sample.csproj
    │   │   │   ├── Program.cs
    │   │   │   └── Properties
    │   │   │       └── launchSettings.json
    │   ├── Directory.Build.props
    │   ├── GettingStarted
    │   │   ├── Checker.cs
    │   │   ├── CountMessage.cs
    │   │   ├── CountUpdate.cs
    │   │   ├── GettingStarted.csproj
    │   │   ├── Modifier.cs
    │   │   └── Program.cs
    │   ├── GettingStartedGrpc
    │   │   ├── Checker.cs
    │   │   ├── GettingStartedGrpc.csproj
    │   │   ├── Modifier.cs
    │   │   ├── Program.cs
    │   │   └── message.proto
    │   ├── Hello
    │   │   ├── Hello.AppHost
    │   │   │   ├── Hello.AppHost.csproj
    │   │   │   ├── Program.cs
    │   │   │   ├── Properties
    │   │   │   │   └── launchSettings.json
    │   │   │   └── appsettings.Development.json
    │   │   ├── HelloAIAgents
    │   │   │   ├── HelloAIAgent.cs
    │   │   │   ├── HelloAIAgents.csproj
    │   │   │   ├── Program.cs
    │   │   │   ├── Properties
    │   │   │   │   └── launchSettings.json
    │   │   │   └── appsettings.json
    │   │   ├── HelloAgent
    │   │   │   ├── HelloAgent.cs
    │   │   │   ├── HelloAgent.csproj
    │   │   │   ├── Program.cs
    │   │   │   ├── Properties
    │   │   │   │   └── launchSettings.json
    │   │   │   ├── README.md
    │   │   │   └── appsettings.json
    │   │   ├── HelloAgentState
    │   │   │   ├── HelloAgentState.csproj
    │   │   │   ├── Program.cs
    │   │   │   ├── Properties
    │   │   │   │   └── launchSettings.json
    │   │   │   ├── README.md
    │   │   │   └── appsettings.json
    │   │   ├── README.md
    │   │   └── protos
    │   │   │   └── agent_events.proto
    │   └── dev-team
    │   │   ├── DevTeam.AppHost
    │   │       ├── DevTeam.AppHost.csproj
    │   │       ├── Program.cs
    │   │       ├── Properties
    │   │       │   └── launchSettings.json
    │   │       └── appsettings.Development.json
    │   │   ├── DevTeam.Backend
    │   │       ├── Agents
    │   │       │   ├── AzureGenie.cs
    │   │       │   ├── Developer
    │   │       │   │   ├── Developer.cs
    │   │       │   │   └── DeveloperPrompts.cs
    │   │       │   ├── DeveloperLead
    │   │       │   │   ├── DeveloperLead.cs
    │   │       │   │   └── DeveloperLeadPrompts.cs
    │   │       │   ├── Hubber.cs
    │   │       │   ├── ProductManager
    │   │       │   │   ├── PMPrompts.cs
    │   │       │   │   └── ProductManager.cs
    │   │       │   └── Sandbox.cs
    │   │       ├── AiAgent.cs
    │   │       ├── Consts.cs
    │   │       ├── DevTeam.Backend.csproj
    │   │       ├── Models
    │   │       │   └── DevPlan.cs
    │   │       ├── Options
    │   │       │   ├── AzureOptions.cs
    │   │       │   └── GithubOptions.cs
    │   │       ├── Program.cs
    │   │       ├── Properties
    │   │       │   └── launchSettings.json
    │   │       ├── Services
    │   │       │   ├── AzureService.cs
    │   │       │   ├── GithubAuthService.cs
    │   │       │   ├── GithubService.cs
    │   │       │   └── GithubWebHookProcessor.cs
    │   │       └── appsettings.Development.json
    │   │   ├── DevTeam.ServiceDefaults
    │   │       ├── DevTeam.ServiceDefaults.csproj
    │   │       └── Extensions.cs
    │   │   ├── Protos
    │   │       ├── messages.proto
    │   │       └── states.proto
    │   │   ├── README.md
    │   │   ├── azure.yaml
    │   │   ├── docs
    │   │       ├── github-flow-getting-started.md
    │   │       └── images
    │   │       │   ├── github-sk-dev-team.png
    │   │       │   ├── new-codespace.png
    │   │       │   ├── overview.png
    │   │       │   └── solution-explorer.png
    │   │   └── seed-memory
    │   │       ├── Dockerfile
    │   │       ├── Program.cs
    │   │       ├── README.md
    │   │       ├── azure-well-architected.pdf
    │   │       ├── config
    │   │           ├── KernelSettings.cs
    │   │           └── appsettings.template.json
    │   │       └── seed-memory.csproj
    ├── spelling.dic
    ├── src
    │   ├── AutoGen.Anthropic
    │   │   ├── Agent
    │   │   │   └── AnthropicClientAgent.cs
    │   │   ├── AnthropicClient.cs
    │   │   ├── AutoGen.Anthropic.csproj
    │   │   ├── Converters
    │   │   │   ├── ContentBaseConverter.cs
    │   │   │   ├── JsonPropertyNameEnumCoverter.cs
    │   │   │   └── SystemMessageConverter.cs
    │   │   ├── DTO
    │   │   │   ├── ChatCompletionRequest.cs
    │   │   │   ├── ChatCompletionResponse.cs
    │   │   │   ├── Content.cs
    │   │   │   ├── ErrorResponse.cs
    │   │   │   ├── Tool.cs
    │   │   │   └── ToolChoice.cs
    │   │   ├── Extensions
    │   │   │   └── AnthropicAgentExtension.cs
    │   │   ├── Middleware
    │   │   │   └── AnthropicMessageConnector.cs
    │   │   └── Utils
    │   │   │   └── AnthropicConstants.cs
    │   ├── AutoGen.AzureAIInference
    │   │   ├── Agent
    │   │   │   └── ChatCompletionsClientAgent.cs
    │   │   ├── AutoGen.AzureAIInference.csproj
    │   │   ├── Extension
    │   │   │   ├── ChatComptionClientAgentExtension.cs
    │   │   │   └── FunctionContractExtension.cs
    │   │   └── Middleware
    │   │   │   └── AzureAIInferenceChatRequestMessageConnector.cs
    │   ├── AutoGen.Core
    │   │   ├── Agent
    │   │   │   ├── DefaultReplyAgent.cs
    │   │   │   ├── GroupChatManager.cs
    │   │   │   ├── IAgent.cs
    │   │   │   ├── IMiddlewareAgent.cs
    │   │   │   ├── IStreamingAgent.cs
    │   │   │   ├── MiddlewareAgent.cs
    │   │   │   └── MiddlewareStreamingAgent.cs
    │   │   ├── AutoGen.Core.csproj
    │   │   ├── Extension
    │   │   │   ├── AgentExtension.cs
    │   │   │   ├── GroupChatExtension.cs
    │   │   │   ├── MessageExtension.cs
    │   │   │   ├── MiddlewareExtension.cs
    │   │   │   ├── PrintMessageMiddlewareExtension.cs
    │   │   │   └── StreamingMiddlewareExtension.cs
    │   │   ├── Function
    │   │   │   └── FunctionAttribute.cs
    │   │   ├── GroupChat
    │   │   │   ├── Graph.cs
    │   │   │   ├── GroupChat.cs
    │   │   │   ├── IGroupChat.cs
    │   │   │   └── RoundRobinGroupChat.cs
    │   │   ├── ILLMConfig.cs
    │   │   ├── Message
    │   │   │   ├── AggregateMessage.cs
    │   │   │   ├── IMessage.cs
    │   │   │   ├── ImageMessage.cs
    │   │   │   ├── Message.cs
    │   │   │   ├── MessageEnvelope.cs
    │   │   │   ├── MultiModalMessage.cs
    │   │   │   ├── Role.cs
    │   │   │   ├── TextMessage.cs
    │   │   │   ├── ToolCallAggregateMessage.cs
    │   │   │   ├── ToolCallMessage.cs
    │   │   │   └── ToolCallResultMessage.cs
    │   │   ├── Middleware
    │   │   │   ├── DelegateMiddleware.cs
    │   │   │   ├── FunctionCallMiddleware.cs
    │   │   │   ├── IMiddleware.cs
    │   │   │   ├── IStreamingMiddleware.cs
    │   │   │   ├── MiddlewareContext.cs
    │   │   │   └── PrintMessageMiddleware.cs
    │   │   └── Orchestrator
    │   │   │   ├── IOrchestrator.cs
    │   │   │   ├── RolePlayOrchestrator.cs
    │   │   │   ├── RoundRobinOrchestrator.cs
    │   │   │   └── WorkflowOrchestrator.cs
    │   ├── AutoGen.DotnetInteractive
    │   │   ├── AutoGen.DotnetInteractive.csproj
    │   │   ├── DotnetInteractiveFunction.cs
    │   │   ├── DotnetInteractiveKernelBuilder.cs
    │   │   ├── DotnetInteractiveStdioKernelConnector.cs
    │   │   ├── Extension
    │   │   │   ├── AgentExtension.cs
    │   │   │   ├── KernelExtension.cs
    │   │   │   └── MessageExtension.cs
    │   │   ├── GlobalUsing.cs
    │   │   ├── InProccessDotnetInteractiveKernelBuilder.cs
    │   │   ├── InteractiveService.cs
    │   │   ├── RestoreInteractive.config
    │   │   └── dotnet-tools.json
    │   ├── AutoGen.Gemini
    │   │   ├── AutoGen.Gemini.csproj
    │   │   ├── Extension
    │   │   │   └── FunctionContractExtension.cs
    │   │   ├── GeminiChatAgent.cs
    │   │   ├── GoogleGeminiClient.cs
    │   │   ├── IGeminiClient.cs
    │   │   ├── Middleware
    │   │   │   ├── GeminiAgentExtension.cs
    │   │   │   └── GeminiMessageConnector.cs
    │   │   └── VertexGeminiClient.cs
    │   ├── AutoGen.LMStudio
    │   │   ├── AutoGen.LMStudio.csproj
    │   │   ├── GlobalUsing.cs
    │   │   ├── LMStudioAgent.cs
    │   │   ├── LMStudioConfig.cs
    │   │   └── README.md
    │   ├── AutoGen.Mistral
    │   │   ├── Agent
    │   │   │   └── MistralClientAgent.cs
    │   │   ├── AutoGen.Mistral.csproj
    │   │   ├── Converters
    │   │   │   └── JsonPropertyNameEnumConverter.cs
    │   │   ├── DTOs
    │   │   │   ├── ChatCompletionRequest.cs
    │   │   │   ├── ChatCompletionResponse.cs
    │   │   │   ├── ChatMessage.cs
    │   │   │   ├── Choice.cs
    │   │   │   ├── Error.cs
    │   │   │   ├── ErrorResponse.cs
    │   │   │   ├── FunctionDefinition.cs
    │   │   │   ├── Model.cs
    │   │   │   ├── ResponseFormat.cs
    │   │   │   ├── Tool.cs
    │   │   │   └── Usage.cs
    │   │   ├── Extension
    │   │   │   ├── FunctionContractExtension.cs
    │   │   │   └── MistralAgentExtension.cs
    │   │   ├── Middleware
    │   │   │   └── MistralChatMessageConnector.cs
    │   │   ├── MistralAIModelID.cs
    │   │   └── MistralClient.cs
    │   ├── AutoGen.Ollama
    │   │   ├── Agent
    │   │   │   └── OllamaAgent.cs
    │   │   ├── AutoGen.Ollama.csproj
    │   │   ├── DTOs
    │   │   │   ├── ChatRequest.cs
    │   │   │   ├── ChatResponse.cs
    │   │   │   ├── ChatResponseUpdate.cs
    │   │   │   ├── Message.cs
    │   │   │   ├── ModelReplyOptions.cs
    │   │   │   └── OllamaReplyOptions.cs
    │   │   ├── Embeddings
    │   │   │   ├── ITextEmbeddingService.cs
    │   │   │   ├── OllamaTextEmbeddingService.cs
    │   │   │   ├── TextEmbeddingsRequest.cs
    │   │   │   └── TextEmbeddingsResponse.cs
    │   │   ├── Extension
    │   │   │   └── OllamaAgentExtension.cs
    │   │   ├── Middlewares
    │   │   │   └── OllamaMessageConnector.cs
    │   │   └── OllamaConsts.cs
    │   ├── AutoGen.OpenAI.V1
    │   │   ├── Agent
    │   │   │   ├── GPTAgent.cs
    │   │   │   └── OpenAIChatAgent.cs
    │   │   ├── AutoGen.OpenAI.V1.csproj
    │   │   ├── AzureOpenAIConfig.cs
    │   │   ├── Extension
    │   │   │   ├── FunctionContractExtension.cs
    │   │   │   ├── MessageExtension.cs
    │   │   │   └── OpenAIAgentExtension.cs
    │   │   ├── GlobalUsing.cs
    │   │   ├── Middleware
    │   │   │   └── OpenAIChatRequestMessageConnector.cs
    │   │   └── OpenAIConfig.cs
    │   ├── AutoGen.OpenAI
    │   │   ├── Agent
    │   │   │   └── OpenAIChatAgent.cs
    │   │   ├── AutoGen.OpenAI.csproj
    │   │   ├── Extension
    │   │   │   ├── FunctionContractExtension.cs
    │   │   │   └── OpenAIAgentExtension.cs
    │   │   ├── GlobalUsing.cs
    │   │   ├── Middleware
    │   │   │   └── OpenAIChatRequestMessageConnector.cs
    │   │   └── Orchestrator
    │   │   │   └── RolePlayToolCallOrchestrator.cs
    │   ├── AutoGen.SemanticKernel
    │   │   ├── AutoGen.SemanticKernel.csproj
    │   │   ├── Extension
    │   │   │   ├── KernelExtension.cs
    │   │   │   └── SemanticKernelAgentExtension.cs
    │   │   ├── GlobalUsing.cs
    │   │   ├── Middleware
    │   │   │   ├── KernelPluginMiddleware.cs
    │   │   │   └── SemanticKernelChatMessageContentConnector.cs
    │   │   ├── SemanticKernelAgent.cs
    │   │   └── SemanticKernelChatCompletionAgent.cs
    │   ├── AutoGen.SourceGenerator
    │   │   ├── AutoGen.SourceGenerator.csproj
    │   │   ├── DocumentCommentExtension.cs
    │   │   ├── FunctionCallGenerator.cs
    │   │   ├── FunctionExtension.cs
    │   │   ├── README.md
    │   │   ├── SourceGeneratorFunctionContract.cs
    │   │   └── Template
    │   │   │   ├── FunctionCallTemplate.cs
    │   │   │   └── FunctionCallTemplate.tt
    │   ├── AutoGen.WebAPI
    │   │   ├── AutoGen.WebAPI.csproj
    │   │   ├── Extension.cs
    │   │   ├── OpenAI
    │   │   │   ├── Converter
    │   │   │   │   └── OpenAIMessageConverter.cs
    │   │   │   ├── DTO
    │   │   │   │   ├── OpenAIAssistantMessage.cs
    │   │   │   │   ├── OpenAIChatCompletion.cs
    │   │   │   │   ├── OpenAIChatCompletionChoice.cs
    │   │   │   │   ├── OpenAIChatCompletionMessage.cs
    │   │   │   │   ├── OpenAIChatCompletionOption.cs
    │   │   │   │   ├── OpenAIChatCompletionUsage.cs
    │   │   │   │   ├── OpenAIImageUrlObject.cs
    │   │   │   │   ├── OpenAIMessage.cs
    │   │   │   │   ├── OpenAIStreamOptions.cs
    │   │   │   │   ├── OpenAISystemMessage.cs
    │   │   │   │   ├── OpenAIToolCallObject.cs
    │   │   │   │   ├── OpenAIToolMessage.cs
    │   │   │   │   ├── OpenAIUserImageContent.cs
    │   │   │   │   ├── OpenAIUserMessage.cs
    │   │   │   │   ├── OpenAIUserMessageItem.cs
    │   │   │   │   ├── OpenAIUserMultiModalMessage.cs
    │   │   │   │   └── OpenAIUserTextContent.cs
    │   │   │   └── Service
    │   │   │   │   └── OpenAIChatCompletionService.cs
    │   │   └── OpenAIChatCompletionMiddleware.cs
    │   ├── AutoGen
    │   │   ├── API
    │   │   │   └── LLMConfigAPI.cs
    │   │   ├── Agent
    │   │   │   ├── AssistantAgent.cs
    │   │   │   ├── ConversableAgent.cs
    │   │   │   └── UserProxyAgent.cs
    │   │   ├── AutoGen.csproj
    │   │   ├── AzureOpenAIConfig.cs
    │   │   ├── ConversableAgentConfig.cs
    │   │   ├── GlobalUsing.cs
    │   │   ├── LMStudioConfig.cs
    │   │   ├── Middleware
    │   │   │   └── HumanInputMiddleware.cs
    │   │   └── OpenAIConfig.cs
    │   └── Microsoft.AutoGen
    │   │   ├── AgentChat
    │   │       ├── Abstractions
    │   │       │   ├── ChatAgent.cs
    │   │       │   ├── Handoff.cs
    │   │       │   ├── ITeam.cs
    │   │       │   ├── MessageHandling.cs
    │   │       │   ├── Messages.cs
    │   │       │   ├── ModelContext.cs
    │   │       │   ├── Tasks.cs
    │   │       │   ├── Termination.cs
    │   │       │   ├── Tools.cs
    │   │       │   └── Usage.cs
    │   │       ├── Agents
    │   │       │   └── ChatAgentBase.cs
    │   │       ├── GroupChat
    │   │       │   ├── ChatAgentRouter.cs
    │   │       │   ├── Events.cs
    │   │       │   ├── GroupChatBase.cs
    │   │       │   ├── GroupChatHandlerRouter.cs
    │   │       │   ├── GroupChatManagerBase.cs
    │   │       │   ├── GroupChatOptions.cs
    │   │       │   ├── HostableAgentAdapter.cs
    │   │       │   ├── OutputCollectorAgent.cs
    │   │       │   ├── RoundRobinGroupChat.cs
    │   │       │   └── RunContext.cs
    │   │       ├── Microsoft.AutoGen.AgentChat.csproj
    │   │       ├── State
    │   │       │   ├── BaseState.cs
    │   │       │   ├── ChatAgentContainerState.cs
    │   │       │   ├── SerializedState.cs
    │   │       │   └── TeamState.cs
    │   │       └── Terminations
    │   │       │   ├── ExternalTermination.cs
    │   │       │   ├── FunctionCallTermination.cs
    │   │       │   ├── HandoffTermination.cs
    │   │       │   ├── MaxMessageTermination.cs
    │   │       │   ├── SourceMatchTermination.cs
    │   │       │   ├── StopMessageTermination.cs
    │   │       │   ├── TextMentionTermination.cs
    │   │       │   ├── TextMessageTermination.cs
    │   │       │   ├── TimeoutTermination.cs
    │   │       │   └── TokenUsageTermination.cs
    │   │   ├── AgentHost
    │   │       ├── .dockerignore
    │   │       ├── Dockerfile
    │   │       ├── Host.cs
    │   │       ├── Microsoft.AutoGen.AgentHost.csproj
    │   │       ├── Program.cs
    │   │       ├── Properties
    │   │       │   └── launchSettings.json
    │   │       └── appsettings.json
    │   │   ├── Agents
    │   │       ├── AIAgent
    │   │       │   └── InferenceAgent.cs
    │   │       ├── IOAgent
    │   │       │   ├── ConsoleAgent
    │   │       │   │   └── IHandleConsole.cs
    │   │       │   ├── FileAgent
    │   │       │   │   └── IHandleFileIO.cs
    │   │       │   └── IProcessIO.cs
    │   │       ├── Microsoft.AutoGen.Agents.csproj
    │   │       └── protos
    │   │       │   └── agent_events.proto
    │   │   ├── Contracts
    │   │       ├── AgentExceptions.cs
    │   │       ├── AgentId.cs
    │   │       ├── AgentMetadata.cs
    │   │       ├── AgentProxy.cs
    │   │       ├── AgentType.cs
    │   │       ├── IAgent.cs
    │   │       ├── IAgentRuntime.cs
    │   │       ├── IHandle.cs
    │   │       ├── ISaveState.cs
    │   │       ├── ISaveStateMixin.cs
    │   │       ├── ISubscriptionDefinition.cs
    │   │       ├── IUnboundSubscriptionDefinition.cs
    │   │       ├── KVStringParseHelper.cs
    │   │       ├── MessageContext.cs
    │   │       ├── Microsoft.AutoGen.Contracts.csproj
    │   │       └── TopicId.cs
    │   │   ├── Core.Grpc
    │   │       ├── AgentExtensions.cs
    │   │       ├── AgentsAppBuilderExtensions.cs
    │   │       ├── CloudEventExtensions.cs
    │   │       ├── Constants.cs
    │   │       ├── GrpcAgentRuntime.cs
    │   │       ├── GrpcMessageRouter.cs
    │   │       ├── IAgentMessageSerializer.cs
    │   │       ├── IAgentRuntimeExtensions.cs
    │   │       ├── IProtobufMessageSerializer.cs
    │   │       ├── ISerializationRegistry.cs
    │   │       ├── ITypeNameResolver.cs
    │   │       ├── Microsoft.AutoGen.Core.Grpc.csproj
    │   │       ├── ProtobufConversionExtensions.cs
    │   │       ├── ProtobufMessageSerializer.cs
    │   │       ├── ProtobufSerializationRegistry.cs
    │   │       ├── ProtobufTypeNameResolver.cs
    │   │       └── RpcExtensions.cs
    │   │   ├── Core
    │   │       ├── AgentRuntimeExtensions.cs
    │   │       ├── AgentsApp.cs
    │   │       ├── BaseAgent.cs
    │   │       ├── HandlerInvoker.cs
    │   │       ├── IHandleExtensions.cs
    │   │       ├── InProcessRuntime.cs
    │   │       ├── MessageDelivery.cs
    │   │       ├── Microsoft.AutoGen.Core.csproj
    │   │       ├── Properties
    │   │       │   └── AssemblyInfo.cs
    │   │       ├── ReflectionHelper.cs
    │   │       ├── ResultSink.cs
    │   │       ├── TypePrefixSubscription.cs
    │   │       ├── TypePrefixSubscriptionAttribute.cs
    │   │       ├── TypeSubscription.cs
    │   │       └── TypeSubscriptionAttribute.cs
    │   │   ├── Extensions
    │   │       ├── Aspire
    │   │       │   ├── AspireHostingExtensions.cs
    │   │       │   └── Microsoft.AutoGen.Extensions.Aspire.csproj
    │   │       ├── MEAI
    │   │       │   ├── MEAIHostingExtensions.cs
    │   │       │   ├── Microsoft.AutoGen.Extensions.MEAI.csproj
    │   │       │   ├── Options
    │   │       │   │   └── AIClientOptions.cs
    │   │       │   └── ServiceCollectionChatCompletionExtensions.cs
    │   │       └── SemanticKernel
    │   │       │   ├── Microsoft.AutoGen.Extensions.SemanticKernel.csproj
    │   │       │   ├── Options
    │   │       │       └── QdrantOptions.cs
    │   │       │   └── SemanticKernelHostingExtensions.cs
    │   │   ├── RuntimeGateway.Grpc
    │   │       ├── Abstractions
    │   │       │   ├── AgentsRegistryState.cs
    │   │       │   ├── IGateway.cs
    │   │       │   ├── IGatewayRegistry.cs
    │   │       │   ├── IMessageRegistryGrain.cs
    │   │       │   ├── IRegistry.cs
    │   │       │   ├── IRegistryGrain.cs
    │   │       │   └── MessageRegistryState.cs
    │   │       ├── Microsoft.AutoGen.RuntimeGateway.Grpc.csproj
    │   │       └── Services
    │   │       │   ├── AgentWorkerHostingExtensions.cs
    │   │       │   ├── Grpc
    │   │       │       ├── GrpcGateway.cs
    │   │       │       ├── GrpcGatewayService.cs
    │   │       │       └── GrpcWorkerConnection.cs
    │   │       │   └── Orleans
    │   │       │       ├── MessageRegistryGrain.cs
    │   │       │       ├── MessageRegistryQueue.cs
    │   │       │       ├── OrleansRuntimeHostingExtenions.cs
    │   │       │       ├── RegistryGrain.cs
    │   │       │       ├── StateManager.cs
    │   │       │       └── Surrogates
    │   │       │           ├── AddSubscriptionRequestSurrogate.cs
    │   │       │           ├── AddSubscriptionResponseSurrogate.cs
    │   │       │           ├── AgentIdSurrogate.cs
    │   │       │           ├── AnySurrogate.cs
    │   │       │           ├── CloudEventSurrogate.cs
    │   │       │           ├── GetSubscriptionsRequest.cs
    │   │       │           ├── RegisterAgentTypeRequestSurrogate.cs
    │   │       │           ├── RegisterAgentTypeResponseSurrogate.cs
    │   │       │           ├── RemoveSubscriptionRequest.cs
    │   │       │           ├── RemoveSubscriptionResponse.cs
    │   │       │           ├── RpcRequestSurrogate.cs
    │   │       │           ├── RpcResponseSurrogate.cs
    │   │       │           ├── SubscriptionSurrogate.cs
    │   │       │           ├── TypePrefixSubscriptionSurrogate.cs
    │   │       │           └── TypeSubscriptionSurrogate.cs
    │   │   └── readme.md
    ├── test
    │   ├── .editorconfig
    │   ├── AutoGen.Anthropic.Tests
    │   │   ├── AnthropicClientAgentTest.cs
    │   │   ├── AnthropicClientTest.cs
    │   │   ├── AnthropicTestFunctionCalls.cs
    │   │   ├── AnthropicTestUtils.cs
    │   │   ├── AutoGen.Anthropic.Tests.csproj
    │   │   └── images
    │   │   │   ├── .gitattributes
    │   │   │   └── square.png
    │   ├── AutoGen.AotCompatibility.Tests
    │   │   ├── AutoGen.AotCompatibility.Tests.csproj
    │   │   └── Program.cs
    │   ├── AutoGen.AzureAIInference.Tests
    │   │   ├── AutoGen.AzureAIInference.Tests.csproj
    │   │   ├── ChatCompletionClientAgentTests.cs
    │   │   └── ChatRequestMessageTests.cs
    │   ├── AutoGen.DotnetInteractive.Tests
    │   │   ├── AutoGen.DotnetInteractive.Tests.csproj
    │   │   ├── DotnetInteractiveServiceTest.cs
    │   │   ├── DotnetInteractiveStdioKernelConnectorTests.cs
    │   │   ├── InProcessDotnetInteractiveKernelBuilderTest.cs
    │   │   └── MessageExtensionTests.cs
    │   ├── AutoGen.Gemini.Tests
    │   │   ├── ApprovalTests
    │   │   │   └── FunctionContractExtensionTests.ItGenerateGetWeatherToolTest.approved.txt
    │   │   ├── AutoGen.Gemini.Tests.csproj
    │   │   ├── FunctionContractExtensionTests.cs
    │   │   ├── Functions.cs
    │   │   ├── GeminiAgentTests.cs
    │   │   ├── GeminiMessageTests.cs
    │   │   ├── GoogleGeminiClientTests.cs
    │   │   ├── SampleTests.cs
    │   │   └── VertexGeminiClientTests.cs
    │   ├── AutoGen.Mistral.Tests
    │   │   ├── AutoGen.Mistral.Tests.csproj
    │   │   ├── MistralClientAgentTests.cs
    │   │   └── MistralClientTests.cs
    │   ├── AutoGen.Ollama.Tests
    │   │   ├── AutoGen.Ollama.Tests.csproj
    │   │   ├── OllamaAgentTests.cs
    │   │   ├── OllamaMessageTests.cs
    │   │   ├── OllamaTextEmbeddingServiceTests.cs
    │   │   └── images
    │   │   │   ├── image.png
    │   │   │   └── square.png
    │   ├── AutoGen.OpenAI.Tests
    │   │   ├── ApprovalTests
    │   │   │   ├── OpenAIMessageTests.BasicMessageTest.approved.txt
    │   │   │   └── OpenAIMessageTests.BasicMessageTest.received.txt
    │   │   ├── AutoGen.OpenAI.Tests.csproj
    │   │   ├── GlobalUsing.cs
    │   │   ├── MathClassTest.cs
    │   │   ├── OpenAIChatAgentTest.cs
    │   │   ├── OpenAIMessageTests.cs
    │   │   ├── OpenAISampleTest.cs
    │   │   └── RolePlayToolCallOrchestratorTests.cs
    │   ├── AutoGen.OpenAI.V1.Tests
    │   │   ├── ApprovalTests
    │   │   │   └── OpenAIMessageTests.BasicMessageTest.approved.txt
    │   │   ├── AutoGen.OpenAI.V1.Tests.csproj
    │   │   ├── GPTAgentTest.cs
    │   │   ├── GlobalUsing.cs
    │   │   ├── MathClassTest.cs
    │   │   ├── OpenAIChatAgentTest.cs
    │   │   └── OpenAIMessageTests.cs
    │   ├── AutoGen.SemanticKernel.Tests
    │   │   ├── ApprovalTests
    │   │   │   ├── KernelFunctionExtensionTests.ItCreateFunctionContractsFromMethod.approved.txt
    │   │   │   ├── KernelFunctionExtensionTests.ItCreateFunctionContractsFromPrompt.approved.txt
    │   │   │   └── KernelFunctionExtensionTests.ItCreateFunctionContractsFromTestPlugin.approved.txt
    │   │   ├── AutoGen.SemanticKernel.Tests.csproj
    │   │   ├── KernelFunctionExtensionTests.cs
    │   │   ├── KernelFunctionMiddlewareTests.cs
    │   │   └── SemanticKernelAgentTest.cs
    │   ├── AutoGen.SourceGenerator.Tests
    │   │   ├── ApprovalTests
    │   │   │   ├── FunctionCallTemplateTests.TestFunctionCallTemplate.approved.txt
    │   │   │   ├── FunctionExample.Add_Test.approved.txt
    │   │   │   ├── FunctionExample.DictionaryToString_Test.approved.txt
    │   │   │   ├── FunctionExample.Query_Test.approved.txt
    │   │   │   └── FunctionExample.Sum_Test.approved.txt
    │   │   ├── AutoGen.SourceGenerator.Tests.csproj
    │   │   ├── FilescopeNamespaceFunctionExample.cs
    │   │   ├── FunctionCallTemplateEncodingTests.cs
    │   │   ├── FunctionCallTemplateTests.cs
    │   │   ├── FunctionExample.test.cs
    │   │   ├── FunctionExamples.cs
    │   │   └── TopLevelStatementFunctionExample.cs
    │   ├── AutoGen.Test.Share
    │   │   ├── Attribute
    │   │   │   ├── EnvironmentSpecificFactAttribute.cs
    │   │   │   └── OpenAIFact.cs
    │   │   ├── AutoGen.Tests.Share.csproj
    │   │   └── EchoAgent.cs
    │   ├── AutoGen.Tests
    │   │   ├── ApprovalTests
    │   │   │   └── square.png
    │   │   ├── AutoGen.Tests.csproj
    │   │   ├── BasicSampleTest.cs
    │   │   ├── Function
    │   │   │   ├── ApprovalTests
    │   │   │   │   └── FunctionTests.CreateGetWeatherFunctionFromAIFunctionFactoryAsync.approved.txt
    │   │   │   └── FunctionTests.cs
    │   │   ├── GlobalUsing.cs
    │   │   ├── GroupChat
    │   │   │   ├── GraphTests.cs
    │   │   │   └── GroupChatTests.cs
    │   │   ├── ImageMessageTests.cs
    │   │   ├── MiddlewareAgentTest.cs
    │   │   ├── MiddlewareTest.cs
    │   │   ├── Orchestrator
    │   │   │   ├── RolePlayOrchestratorTests.cs
    │   │   │   ├── RoundRobinOrchestratorTests.cs
    │   │   │   └── WorkflowOrchestratorTests.cs
    │   │   ├── SingleAgentTest.cs
    │   │   ├── TwoAgentTest.cs
    │   │   └── WorkflowTest.cs
    │   ├── AutoGen.WebAPI.Tests
    │   │   ├── AutoGen.WebAPI.Tests.csproj
    │   │   ├── EchoAgent.cs
    │   │   └── OpenAIChatCompletionMiddlewareTests.cs
    │   ├── Microsoft.AutoGen.AgentChat.Tests
    │   │   ├── AgentChatSmokeTest.cs
    │   │   ├── LifecycleObjectTests.cs
    │   │   ├── Microsoft.AutoGen.AgentChat.Tests.csproj
    │   │   ├── RunContextStackTests.cs
    │   │   └── TerminationConditionTests.cs
    │   ├── Microsoft.AutoGen.Core.Grpc.Tests
    │   │   ├── AgentGrpcTests.cs
    │   │   ├── FreePortManager.cs
    │   │   ├── GrpcAgentRuntimeFixture.cs
    │   │   ├── GrpcAgentRuntimeTests.cs
    │   │   ├── GrpcAgentServiceFixture.cs
    │   │   ├── Microsoft.AutoGen.Core.Grpc.Tests.csproj
    │   │   ├── Properties
    │   │   │   └── launchSettings.json
    │   │   ├── TestBase.cs
    │   │   ├── TestGrpcWorkerConnection.cs
    │   │   ├── TestProtobufAgent.cs
    │   │   ├── appsettings.json
    │   │   └── messages.proto
    │   ├── Microsoft.AutoGen.Core.Tests
    │   │   ├── AgentIdTests.cs
    │   │   ├── AgentMetaDataTests.cs
    │   │   ├── AgentTests.cs
    │   │   ├── HandlerInvokerTest.cs
    │   │   ├── InProcessRuntimeExtensions.cs
    │   │   ├── InProcessRuntimeTests.cs
    │   │   ├── MessagingTestFixture.cs
    │   │   ├── Microsoft.AutoGen.Core.Tests.csproj
    │   │   ├── PublishMessageTests.cs
    │   │   ├── SendMessageTests.cs
    │   │   ├── TestAgents.cs
    │   │   └── TestMessages.cs
    │   ├── Microsoft.AutoGen.Integration.Tests.AppHosts
    │   │   ├── HelloAgentTests
    │   │   │   ├── HelloAgent.cs
    │   │   │   ├── HelloAgentTests.csproj
    │   │   │   ├── Program.cs
    │   │   │   ├── Properties
    │   │   │   │   └── launchSettings.json
    │   │   │   ├── README.md
    │   │   │   └── appsettings.json
    │   │   ├── InMemoryTests.AppHost
    │   │   │   ├── InMemoryTests.AppHost.csproj
    │   │   │   ├── Program.cs
    │   │   │   └── Properties
    │   │   │   │   └── launchSettings.json
    │   │   ├── XLangTests.AppHost
    │   │   │   ├── Program.cs
    │   │   │   ├── Properties
    │   │   │   │   └── launchSettings.json
    │   │   │   └── XlangTests.AppHost.csproj
    │   │   ├── core_xlang_hello_python_agent
    │   │   │   ├── README.md
    │   │   │   ├── hello_python_agent.py
    │   │   │   ├── protos
    │   │   │   │   ├── __init__.py
    │   │   │   │   ├── agent_events_pb2.py
    │   │   │   │   ├── agent_events_pb2.pyi
    │   │   │   │   ├── agent_events_pb2_grpc.py
    │   │   │   │   └── agent_events_pb2_grpc.pyi
    │   │   │   └── user_input.py
    │   │   └── protos
    │   │   │   └── agent_events.proto
    │   ├── Microsoft.AutoGen.Integration.Tests
    │   │   ├── HelloAppHostIntegrationTests.cs
    │   │   ├── InMemoryRuntimeIntegrationTests.cs
    │   │   ├── Infrastructure
    │   │   │   ├── DistributedApplicationExtension.cs
    │   │   │   └── DistributedApplicationTestFactory.cs
    │   │   ├── Microsoft.AutoGen.Integration.Tests.csproj
    │   │   └── Properties
    │   │   │   └── launchSettings.json
    │   ├── Microsoft.AutoGen.RuntimeGateway.Grpc.Tests
    │   │   ├── GrpcGatewayServiceTests.cs
    │   │   ├── Helpers
    │   │   │   ├── AgentTypes.cs
    │   │   │   ├── AgentsMetadata.cs
    │   │   │   ├── Grpc
    │   │   │   │   ├── TestAsyncStreamReader.cs
    │   │   │   │   ├── TestGrpcClient.cs
    │   │   │   │   ├── TestServerCallContext.cs
    │   │   │   │   └── TestServerStreamWriter.cs
    │   │   │   ├── Orleans
    │   │   │   │   ├── ClusterCollection.cs
    │   │   │   │   ├── ClusterFixture.cs
    │   │   │   │   └── SiloBuilderConfigurator.cs
    │   │   │   └── ReflectionHelper.cs
    │   │   ├── MessageRegistryTests.cs
    │   │   ├── Microsoft.AutoGen.RuntimeGateway.Grpc.Tests.csproj
    │   │   └── TestAgent.cs
    │   └── Microsoft.AutoGen.Tests.Shared
    │   │   ├── Microsoft.AutoGen.Tests.Shared.csproj
    │   │   └── Protos
    │   │       └── messages.proto
    └── website
    │   ├── .gitignore
    │   ├── README.md
    │   ├── articles
    │       ├── Agent-overview.md
    │       ├── AutoGen-Mistral-Overview.md
    │       ├── AutoGen-OpenAI-Overview.md
    │       ├── AutoGen.Gemini
    │       │   ├── Chat-with-google-gemini.md
    │       │   ├── Chat-with-vertex-gemini.md
    │       │   ├── Function-call-with-gemini.md
    │       │   ├── Image-chat-with-gemini.md
    │       │   └── Overview.md
    │       ├── AutoGen.Ollama
    │       │   ├── Chat-with-llama.md
    │       │   └── Chat-with-llava.md
    │       ├── AutoGen.SemanticKernel
    │       │   ├── AutoGen-SemanticKernel-Overview.md
    │       │   ├── SemanticKernelAgent-simple-chat.md
    │       │   ├── SemanticKernelAgent-support-more-messages.md
    │       │   ├── SemanticKernelChatAgent-simple-chat.md
    │       │   └── Use-kernel-plugin-in-other-agents.md
    │       ├── Built-in-messages.md
    │       ├── Consume-LLM-server-from-LM-Studio.md
    │       ├── Create-a-user-proxy-agent.md
    │       ├── Create-an-agent.md
    │       ├── Create-type-safe-function-call.md
    │       ├── Create-your-own-agent.md
    │       ├── Create-your-own-middleware.md
    │       ├── Function-call-middleware.md
    │       ├── Function-call-overview.md
    │       ├── Function-call-with-ollama-and-litellm.md
    │       ├── Group-chat-overview.md
    │       ├── Group-chat.md
    │       ├── Installation.md
    │       ├── Middleware-overview.md
    │       ├── MistralChatAgent-count-token-usage.md
    │       ├── MistralChatAgent-use-function-call.md
    │       ├── OpenAIChatAgent-connect-to-third-party-api.md
    │       ├── OpenAIChatAgent-simple-chat.md
    │       ├── OpenAIChatAgent-support-more-messages.md
    │       ├── OpenAIChatAgent-use-function-call.md
    │       ├── OpenAIChatAgent-use-json-mode.md
    │       ├── Print-message-middleware.md
    │       ├── Roundrobin-chat.md
    │       ├── Run-dotnet-code.md
    │       ├── Two-agent-chat.md
    │       ├── Use-function-call.md
    │       ├── Use-graph-in-group-chat.md
    │       ├── function-comparison-page-between-python-AutoGen-and-autogen.net.md
    │       ├── getting-start.md
    │       └── toc.yml
    │   ├── docfx.json
    │   ├── filterConfig.yml
    │   ├── images
    │       ├── ag.ico
    │       ├── ag.svg
    │       └── articles
    │       │   ├── ConnectTo3PartyOpenAI
    │       │       └── output.gif
    │       │   ├── CreateAgentWithTools
    │       │       ├── single-turn-tool-call-with-auto-invoke.png
    │       │       └── single-turn-tool-call-without-auto-invoke.png
    │       │   ├── CreateUserProxyAgent
    │       │       └── image-1.png
    │       │   ├── DynamicGroupChat
    │       │       └── dynamicChat.gif
    │       │   ├── PrintMessageMiddleware
    │       │       ├── printMessage.png
    │       │       └── streamingoutput.gif
    │       │   ├── SequentialGroupChat
    │       │       └── SearcherSummarizer.gif
    │       │   └── UseAutoGenAsModelinAGStudio
    │       │       ├── FinalStepsA.png
    │       │       ├── FinalStepsB.png
    │       │       ├── FinalStepsC.png
    │       │       ├── Step5.2OpenAIModel.png
    │       │       ├── Step5.3ModelNameAndURL.png
    │       │       ├── Step6.png
    │       │       ├── Step6b.png
    │       │       ├── Terminal.png
    │       │       └── TheModelTab.png
    │   ├── index.md
    │   ├── release_note
    │       ├── 0.0.16.md
    │       ├── 0.0.17.md
    │       ├── 0.1.0.md
    │       ├── 0.2.0.md
    │       ├── 0.2.1.md
    │       ├── 0.2.2.md
    │       ├── toc.yml
    │       └── update.md
    │   ├── template
    │       └── public
    │       │   └── main.js
    │   ├── toc.yml
    │   └── tutorial
    │       ├── Chat-with-an-agent.md
    │       ├── Create-agent-with-tools.md
    │       ├── Image-chat-with-agent.md
    │       ├── Use-AutoGen.Net-agent-as-model-in-AG-Studio.md
    │       └── toc.yml
├── protos
    ├── agent_worker.proto
    └── cloudevent.proto
└── python
    ├── .gitignore
    ├── README.md
    ├── check_md_code_blocks.py
    ├── docs
        ├── README.md
        ├── drawio
        │   ├── agent-lifecycle.drawio
        │   ├── agentchat-team.drawio
        │   ├── application-stack.drawio
        │   ├── architecture-distributed.drawio
        │   ├── architecture-standalone.drawio
        │   ├── assistant-agent.drawio
        │   ├── code-gen-example.drawio
        │   ├── coder-reviewer.drawio
        │   ├── groupchat.drawio
        │   ├── handoffs.drawio
        │   ├── human-in-the-loop-termination.drawio
        │   ├── human-in-the-loop-user-proxy.drawio
        │   ├── selector-group-chat.drawio
        │   ├── sequential-workflow.drawio
        │   ├── subscription.drawio
        │   ├── swarm_customer_support.drawio
        │   ├── swarm_stock_research.drawio
        │   └── type-subscription.drawio
        ├── redirects
        │   ├── redirect_template.html
        │   ├── redirect_urls.txt
        │   └── redirects.py
        └── src
        │   ├── _apidoc_templates
        │       ├── module.rst.jinja
        │       └── package.rst.jinja
        │   ├── _extension
        │       ├── code_lint.py
        │       └── gallery_directive.py
        │   ├── _static
        │       ├── banner-override.js
        │       ├── custom-icon.js
        │       ├── custom.css
        │       ├── custom.js
        │       ├── images
        │       │   └── logo
        │       │   │   ├── favicon-16x16.png
        │       │   │   ├── favicon-32x32.png
        │       │   │   ├── favicon-512x512.png
        │       │   │   ├── favicon.ico
        │       │   │   └── logo.svg
        │       └── switcher.json
        │   ├── _templates
        │       ├── edit-this-page.html
        │       ├── footer-middle-links.html
        │       ├── sidebar-nav-bs-agentchat.html
        │       ├── sidebar-nav-bs-core.html
        │       ├── sidebar-nav-bs-extensions.html
        │       ├── sidebar-nav-bs-studio.html
        │       ├── sidebar-nav-bs.html
        │       ├── theme-switcher.html
        │       └── version-banner-override.html
        │   ├── conf.py
        │   ├── generate_api_reference.py
        │   ├── images
        │       ├── assistant-agent.svg
        │       ├── autogen-magentic-one-agents.png
        │       ├── autogen-magentic-one-example.png
        │       ├── code.svg
        │       ├── example-company.jpg
        │       ├── example-literature.jpg
        │       ├── example-travel.jpeg
        │       └── open-ai-telemetry-example.png
        │   ├── index.md
        │   └── user-guide
        │       ├── agentchat-user-guide
        │           ├── custom-agents.ipynb
        │           ├── examples
        │           │   ├── company-research.ipynb
        │           │   ├── index.md
        │           │   ├── literature-review.ipynb
        │           │   └── travel-planning.ipynb
        │           ├── graph-flow.ipynb
        │           ├── index.md
        │           ├── installation.md
        │           ├── jaeger.png
        │           ├── logging.md
        │           ├── magentic-one.md
        │           ├── memory.ipynb
        │           ├── migration-guide.md
        │           ├── quickstart.ipynb
        │           ├── selector-group-chat.ipynb
        │           ├── selector-group-chat.svg
        │           ├── serialize-components.ipynb
        │           ├── swarm.ipynb
        │           ├── swarm_customer_support.svg
        │           ├── swarm_stock_research.svg
        │           ├── tracing.ipynb
        │           └── tutorial
        │           │   ├── .gitignore
        │           │   ├── agentchat-team.svg
        │           │   ├── agents.ipynb
        │           │   ├── human-in-the-loop-termination.svg
        │           │   ├── human-in-the-loop-user-proxy.svg
        │           │   ├── human-in-the-loop.ipynb
        │           │   ├── index.md
        │           │   ├── messages.ipynb
        │           │   ├── models.ipynb
        │           │   ├── state.ipynb
        │           │   ├── teams.ipynb
        │           │   └── termination.ipynb
        │       ├── autogenstudio-user-guide
        │           ├── experimental.md
        │           ├── faq.md
        │           ├── index.md
        │           ├── installation.md
        │           ├── jsoneditor.jpg
        │           ├── teambuilder.jpg
        │           └── usage.md
        │       ├── core-user-guide
        │           ├── components
        │           │   ├── command-line-code-executors.ipynb
        │           │   ├── model-clients.ipynb
        │           │   ├── model-context.ipynb
        │           │   ├── tools.ipynb
        │           │   └── workbench.ipynb
        │           ├── cookbook
        │           │   ├── azure-openai-with-aad-auth.md
        │           │   ├── data
        │           │   │   └── nifty_500_quarterly_results.csv
        │           │   ├── extracting-results-with-an-agent.ipynb
        │           │   ├── index.md
        │           │   ├── instrumenting.md
        │           │   ├── langgraph-agent.ipynb
        │           │   ├── llamaindex-agent.ipynb
        │           │   ├── llm-usage-logger.ipynb
        │           │   ├── local-llms-ollama-litellm.ipynb
        │           │   ├── openai-assistant-agent.ipynb
        │           │   ├── structured-output-agent.ipynb
        │           │   ├── termination-with-intervention.ipynb
        │           │   ├── tool-use-with-intervention.ipynb
        │           │   └── topic-subscription-scenarios.ipynb
        │           ├── core-concepts
        │           │   ├── agent-and-multi-agent-application.md
        │           │   ├── agent-identity-and-lifecycle.md
        │           │   ├── agent-lifecycle.svg
        │           │   ├── application-stack.md
        │           │   ├── application-stack.svg
        │           │   ├── architecture-distributed.svg
        │           │   ├── architecture-standalone.svg
        │           │   ├── architecture.md
        │           │   ├── code-gen-example.svg
        │           │   ├── subscription.svg
        │           │   ├── topic-and-subscription.md
        │           │   ├── type-subscription-multi-tenant.svg
        │           │   ├── type-subscription-single-tenant-multiple-topics.svg
        │           │   └── type-subscription-single-tenant-single-topic.svg
        │           ├── design-patterns
        │           │   ├── code-execution-groupchat.ipynb
        │           │   ├── coder-reviewer-data-flow.svg
        │           │   ├── concurrent-agents.ipynb
        │           │   ├── group-chat.ipynb
        │           │   ├── groupchat.svg
        │           │   ├── handoffs.ipynb
        │           │   ├── handoffs.svg
        │           │   ├── intro.md
        │           │   ├── mixture-of-agents.ipynb
        │           │   ├── multi-agent-debate.ipynb
        │           │   ├── reflection.ipynb
        │           │   ├── sequential-workflow.ipynb
        │           │   └── sequential-workflow.svg
        │           ├── faqs.md
        │           ├── framework
        │           │   ├── agent-and-agent-runtime.ipynb
        │           │   ├── component-config.ipynb
        │           │   ├── distributed-agent-runtime.ipynb
        │           │   ├── logging.md
        │           │   ├── message-and-communication.ipynb
        │           │   └── telemetry.md
        │           ├── index.md
        │           ├── installation.md
        │           └── quickstart.ipynb
        │       └── extensions-user-guide
        │           ├── azure-container-code-executor.ipynb
        │           ├── azure-foundry-agent.ipynb
        │           ├── create-your-own.md
        │           ├── discover.md
        │           ├── index.md
        │           └── installation.md
    ├── fixup_generated_files.py
    ├── packages
        ├── agbench
        │   ├── .gitignore
        │   ├── CONTRIBUTING.md
        │   ├── LICENSE-CODE
        │   ├── MANIFEST.in
        │   ├── README.md
        │   ├── benchmarks
        │   │   ├── .gitignore
        │   │   ├── GAIA
        │   │   │   ├── .gitignore
        │   │   │   ├── ENV.yaml
        │   │   │   ├── README.md
        │   │   │   ├── Scripts
        │   │   │   │   ├── custom_tabulate.py
        │   │   │   │   └── init_tasks.py
        │   │   │   ├── Templates
        │   │   │   │   ├── MagenticOne
        │   │   │   │   │   ├── expected_answer.txt
        │   │   │   │   │   ├── prompt.txt
        │   │   │   │   │   ├── requirements.txt
        │   │   │   │   │   └── scenario.py
        │   │   │   │   ├── ParallelAgents
        │   │   │   │   │   ├── expected_answer.txt
        │   │   │   │   │   ├── prompt.txt
        │   │   │   │   │   ├── requirements.txt
        │   │   │   │   │   └── scenario.py
        │   │   │   │   └── SelectorGroupChat
        │   │   │   │   │   ├── expected_answer.txt
        │   │   │   │   │   ├── prompt.txt
        │   │   │   │   │   ├── requirements.txt
        │   │   │   │   │   └── scenario.py
        │   │   │   └── config.yaml
        │   │   ├── HumanEval
        │   │   │   ├── ENV.yaml
        │   │   │   ├── README.md
        │   │   │   ├── Scripts
        │   │   │   │   ├── custom_tabulate.py
        │   │   │   │   └── init_tasks.py
        │   │   │   ├── Templates
        │   │   │   │   └── AgentChat
        │   │   │   │   │   ├── custom_code_executor.py
        │   │   │   │   │   ├── prompt.txt
        │   │   │   │   │   ├── reasoning_model_context.py
        │   │   │   │   │   ├── requirements.txt
        │   │   │   │   │   ├── scenario.py
        │   │   │   │   │   └── test.txt
        │   │   │   └── config.yaml
        │   │   ├── README.md
        │   │   └── process_logs.py
        │   ├── pyproject.toml
        │   ├── setup.py
        │   └── src
        │   │   └── agbench
        │   │       ├── __init__.py
        │   │       ├── __main__.py
        │   │       ├── cli.py
        │   │       ├── linter
        │   │           ├── __init__.py
        │   │           ├── _base.py
        │   │           ├── cli.py
        │   │           └── coders
        │   │           │   ├── __init__.py
        │   │           │   └── oai_coder.py
        │   │       ├── load_module.py
        │   │       ├── remove_missing_cmd.py
        │   │       ├── res
        │   │           └── Dockerfile
        │   │       ├── run_cmd.py
        │   │       ├── tabulate_cmd.py
        │   │       ├── template
        │   │           ├── global_finalize.sh
        │   │           ├── global_init.sh
        │   │           └── requirements.txt
        │   │       └── version.py
        ├── autogen-agentchat
        │   ├── LICENSE-CODE
        │   ├── README.md
        │   ├── pyproject.toml
        │   ├── src
        │   │   └── autogen_agentchat
        │   │   │   ├── __init__.py
        │   │   │   ├── agents
        │   │   │       ├── __init__.py
        │   │   │       ├── _assistant_agent.py
        │   │   │       ├── _base_chat_agent.py
        │   │   │       ├── _code_executor_agent.py
        │   │   │       ├── _message_filter_agent.py
        │   │   │       ├── _society_of_mind_agent.py
        │   │   │       └── _user_proxy_agent.py
        │   │   │   ├── base
        │   │   │       ├── __init__.py
        │   │   │       ├── _chat_agent.py
        │   │   │       ├── _handoff.py
        │   │   │       ├── _task.py
        │   │   │       ├── _team.py
        │   │   │       └── _termination.py
        │   │   │   ├── conditions
        │   │   │       ├── __init__.py
        │   │   │       └── _terminations.py
        │   │   │   ├── messages.py
        │   │   │   ├── py.typed
        │   │   │   ├── state
        │   │   │       ├── __init__.py
        │   │   │       └── _states.py
        │   │   │   ├── teams
        │   │   │       ├── __init__.py
        │   │   │       └── _group_chat
        │   │   │       │   ├── __init__.py
        │   │   │       │   ├── _base_group_chat.py
        │   │   │       │   ├── _base_group_chat_manager.py
        │   │   │       │   ├── _chat_agent_container.py
        │   │   │       │   ├── _events.py
        │   │   │       │   ├── _graph
        │   │   │       │       ├── __init__.py
        │   │   │       │       ├── _digraph_group_chat.py
        │   │   │       │       └── _graph_builder.py
        │   │   │       │   ├── _magentic_one
        │   │   │       │       ├── __init__.py
        │   │   │       │       ├── _magentic_one_group_chat.py
        │   │   │       │       ├── _magentic_one_orchestrator.py
        │   │   │       │       └── _prompts.py
        │   │   │       │   ├── _round_robin_group_chat.py
        │   │   │       │   ├── _selector_group_chat.py
        │   │   │       │   ├── _sequential_routed_agent.py
        │   │   │       │   └── _swarm_group_chat.py
        │   │   │   ├── tools
        │   │   │       ├── __init__.py
        │   │   │       ├── _agent.py
        │   │   │       ├── _task_runner_tool.py
        │   │   │       └── _team.py
        │   │   │   ├── ui
        │   │   │       ├── __init__.py
        │   │   │       └── _console.py
        │   │   │   └── utils
        │   │   │       ├── __init__.py
        │   │   │       └── _utils.py
        │   └── tests
        │   │   ├── test_agent.py
        │   │   ├── test_assistant_agent.py
        │   │   ├── test_code_executor_agent.py
        │   │   ├── test_declarative_components.py
        │   │   ├── test_group_chat.py
        │   │   ├── test_group_chat_endpoint.py
        │   │   ├── test_group_chat_graph.py
        │   │   ├── test_group_chat_pause_resume.py
        │   │   ├── test_magentic_one_group_chat.py
        │   │   ├── test_messages.py
        │   │   ├── test_sequential_routed_agent.py
        │   │   ├── test_society_of_mind_agent.py
        │   │   ├── test_streaming_message_id_correlation.py
        │   │   ├── test_task_runner_tool.py
        │   │   ├── test_termination_condition.py
        │   │   ├── test_userproxy_agent.py
        │   │   ├── test_utils.py
        │   │   └── utils.py
        ├── autogen-core
        │   ├── .gitignore
        │   ├── LICENSE-CODE
        │   ├── README.md
        │   ├── pyproject.toml
        │   ├── src
        │   │   └── autogen_core
        │   │   │   ├── __init__.py
        │   │   │   ├── _agent.py
        │   │   │   ├── _agent_id.py
        │   │   │   ├── _agent_instantiation.py
        │   │   │   ├── _agent_metadata.py
        │   │   │   ├── _agent_proxy.py
        │   │   │   ├── _agent_runtime.py
        │   │   │   ├── _agent_type.py
        │   │   │   ├── _base_agent.py
        │   │   │   ├── _cache_store.py
        │   │   │   ├── _cancellation_token.py
        │   │   │   ├── _closure_agent.py
        │   │   │   ├── _component_config.py
        │   │   │   ├── _constants.py
        │   │   │   ├── _default_subscription.py
        │   │   │   ├── _default_topic.py
        │   │   │   ├── _function_utils.py
        │   │   │   ├── _image.py
        │   │   │   ├── _intervention.py
        │   │   │   ├── _message_context.py
        │   │   │   ├── _message_handler_context.py
        │   │   │   ├── _queue.py
        │   │   │   ├── _routed_agent.py
        │   │   │   ├── _runtime_impl_helpers.py
        │   │   │   ├── _serialization.py
        │   │   │   ├── _single_threaded_agent_runtime.py
        │   │   │   ├── _subscription.py
        │   │   │   ├── _subscription_context.py
        │   │   │   ├── _telemetry
        │   │   │       ├── __init__.py
        │   │   │       ├── _constants.py
        │   │   │       ├── _genai.py
        │   │   │       ├── _propagation.py
        │   │   │       ├── _tracing.py
        │   │   │       └── _tracing_config.py
        │   │   │   ├── _topic.py
        │   │   │   ├── _type_helpers.py
        │   │   │   ├── _type_prefix_subscription.py
        │   │   │   ├── _type_subscription.py
        │   │   │   ├── _types.py
        │   │   │   ├── code_executor
        │   │   │       ├── __init__.py
        │   │   │       ├── _base.py
        │   │   │       └── _func_with_reqs.py
        │   │   │   ├── exceptions.py
        │   │   │   ├── logging.py
        │   │   │   ├── memory
        │   │   │       ├── __init__.py
        │   │   │       ├── _base_memory.py
        │   │   │       └── _list_memory.py
        │   │   │   ├── model_context
        │   │   │       ├── __init__.py
        │   │   │       ├── _buffered_chat_completion_context.py
        │   │   │       ├── _chat_completion_context.py
        │   │   │       ├── _head_and_tail_chat_completion_context.py
        │   │   │       ├── _token_limited_chat_completion_context.py
        │   │   │       └── _unbounded_chat_completion_context.py
        │   │   │   ├── models
        │   │   │       ├── __init__.py
        │   │   │       ├── _model_client.py
        │   │   │       └── _types.py
        │   │   │   ├── py.typed
        │   │   │   ├── tool_agent
        │   │   │       ├── __init__.py
        │   │   │       ├── _caller_loop.py
        │   │   │       └── _tool_agent.py
        │   │   │   ├── tools
        │   │   │       ├── __init__.py
        │   │   │       ├── _base.py
        │   │   │       ├── _function_tool.py
        │   │   │       ├── _static_workbench.py
        │   │   │       └── _workbench.py
        │   │   │   └── utils
        │   │   │       ├── __init__.py
        │   │   │       ├── _json_to_pydantic.py
        │   │   │       └── _load_json.py
        │   └── tests
        │   │   ├── protos
        │   │       ├── serialization_test.proto
        │   │       ├── serialization_test_pb2.py
        │   │       ├── serialization_test_pb2.pyi
        │   │       ├── serialization_test_pb2_grpc.py
        │   │       └── serialization_test_pb2_grpc.pyi
        │   │   ├── regressions
        │   │       └── test_clean_terminate.py
        │   │   ├── test_base_agent.py
        │   │   ├── test_cache_store.py
        │   │   ├── test_cancellation.py
        │   │   ├── test_closure_agent.py
        │   │   ├── test_code_executor.py
        │   │   ├── test_component_config.py
        │   │   ├── test_intervention.py
        │   │   ├── test_json_extraction.py
        │   │   ├── test_json_to_pydantic.py
        │   │   ├── test_memory.py
        │   │   ├── test_model_context.py
        │   │   ├── test_models.py
        │   │   ├── test_routed_agent.py
        │   │   ├── test_runtime.py
        │   │   ├── test_serialization.py
        │   │   ├── test_state.py
        │   │   ├── test_static_workbench_overrides.py
        │   │   ├── test_subscription.py
        │   │   ├── test_tool_agent.py
        │   │   ├── test_tools.py
        │   │   ├── test_types.py
        │   │   └── test_workbench.py
        ├── autogen-ext
        │   ├── LICENSE-CODE
        │   ├── README.md
        │   ├── conftest.py
        │   ├── imgs
        │   │   ├── task_centric_memory.png
        │   │   ├── task_centric_memory_2.png
        │   │   └── task_centric_memory_3.png
        │   ├── pyproject.toml
        │   ├── src
        │   │   └── autogen_ext
        │   │   │   ├── __init__.py
        │   │   │   ├── agents
        │   │   │       ├── azure
        │   │   │       │   ├── __init__.py
        │   │   │       │   ├── _azure_ai_agent.py
        │   │   │       │   └── _types.py
        │   │   │       ├── file_surfer
        │   │   │       │   ├── __init__.py
        │   │   │       │   ├── _file_surfer.py
        │   │   │       │   ├── _markdown_file_browser.py
        │   │   │       │   └── _tool_definitions.py
        │   │   │       ├── magentic_one
        │   │   │       │   ├── __init__.py
        │   │   │       │   └── _magentic_one_coder_agent.py
        │   │   │       ├── openai
        │   │   │       │   ├── __init__.py
        │   │   │       │   ├── _openai_agent.py
        │   │   │       │   └── _openai_assistant_agent.py
        │   │   │       ├── video_surfer
        │   │   │       │   ├── __init__.py
        │   │   │       │   ├── _video_surfer.py
        │   │   │       │   └── tools.py
        │   │   │       └── web_surfer
        │   │   │       │   ├── __init__.py
        │   │   │       │   ├── _events.py
        │   │   │       │   ├── _multimodal_web_surfer.py
        │   │   │       │   ├── _prompts.py
        │   │   │       │   ├── _set_of_mark.py
        │   │   │       │   ├── _tool_definitions.py
        │   │   │       │   ├── _types.py
        │   │   │       │   ├── page_script.js
        │   │   │       │   └── playwright_controller.py
        │   │   │   ├── auth
        │   │   │       └── azure
        │   │   │       │   └── __init__.py
        │   │   │   ├── cache_store
        │   │   │       ├── __init__.py
        │   │   │       ├── diskcache.py
        │   │   │       └── redis.py
        │   │   │   ├── code_executors
        │   │   │       ├── _common.py
        │   │   │       ├── azure
        │   │   │       │   ├── __init__.py
        │   │   │       │   └── _azure_container_code_executor.py
        │   │   │       ├── docker
        │   │   │       │   ├── __init__.py
        │   │   │       │   └── _docker_code_executor.py
        │   │   │       ├── docker_jupyter
        │   │   │       │   ├── __init__.py
        │   │   │       │   ├── _docker_jupyter.py
        │   │   │       │   └── _jupyter_server.py
        │   │   │       ├── jupyter
        │   │   │       │   ├── __init__.py
        │   │   │       │   └── _jupyter_code_executor.py
        │   │   │       └── local
        │   │   │       │   └── __init__.py
        │   │   │   ├── experimental
        │   │   │       ├── __init__.py
        │   │   │       └── task_centric_memory
        │   │   │       │   ├── README.md
        │   │   │       │   ├── __init__.py
        │   │   │       │   ├── _memory_bank.py
        │   │   │       │   ├── _prompter.py
        │   │   │       │   ├── _string_similarity_map.py
        │   │   │       │   ├── memory_controller.py
        │   │   │       │   └── utils
        │   │   │       │       ├── __init__.py
        │   │   │       │       ├── _functions.py
        │   │   │       │       ├── apprentice.py
        │   │   │       │       ├── chat_completion_client_recorder.py
        │   │   │       │       ├── grader.py
        │   │   │       │       ├── page_logger.py
        │   │   │       │       └── teachability.py
        │   │   │   ├── memory
        │   │   │       ├── __init__.py
        │   │   │       ├── canvas
        │   │   │       │   ├── __init__.py
        │   │   │       │   ├── _canvas.py
        │   │   │       │   ├── _canvas_writer.py
        │   │   │       │   ├── _text_canvas.py
        │   │   │       │   └── _text_canvas_memory.py
        │   │   │       ├── chromadb
        │   │   │       │   ├── __init__.py
        │   │   │       │   ├── _chroma_configs.py
        │   │   │       │   └── _chromadb.py
        │   │   │       └── mem0
        │   │   │       │   ├── __init__.py
        │   │   │       │   └── _mem0.py
        │   │   │   ├── models
        │   │   │       ├── __init__.py
        │   │   │       ├── _utils
        │   │   │       │   ├── normalize_stop_reason.py
        │   │   │       │   └── parse_r1_content.py
        │   │   │       ├── anthropic
        │   │   │       │   ├── __init__.py
        │   │   │       │   ├── _anthropic_client.py
        │   │   │       │   ├── _model_info.py
        │   │   │       │   └── config
        │   │   │       │   │   └── __init__.py
        │   │   │       ├── azure
        │   │   │       │   ├── __init__.py
        │   │   │       │   ├── _azure_ai_client.py
        │   │   │       │   └── config
        │   │   │       │   │   └── __init__.py
        │   │   │       ├── cache
        │   │   │       │   ├── __init__.py
        │   │   │       │   └── _chat_completion_cache.py
        │   │   │       ├── llama_cpp
        │   │   │       │   ├── __init__.py
        │   │   │       │   └── _llama_cpp_completion_client.py
        │   │   │       ├── ollama
        │   │   │       │   ├── __init__.py
        │   │   │       │   ├── _model_info.py
        │   │   │       │   ├── _ollama_client.py
        │   │   │       │   └── config
        │   │   │       │   │   └── __init__.py
        │   │   │       ├── openai
        │   │   │       │   ├── __init__.py
        │   │   │       │   ├── _message_transform.py
        │   │   │       │   ├── _model_info.py
        │   │   │       │   ├── _openai_client.py
        │   │   │       │   ├── _transformation
        │   │   │       │   │   ├── __init__.py
        │   │   │       │   │   ├── registry.py
        │   │   │       │   │   └── types.py
        │   │   │       │   ├── _utils.py
        │   │   │       │   └── config
        │   │   │       │   │   └── __init__.py
        │   │   │       ├── replay
        │   │   │       │   ├── __init__.py
        │   │   │       │   └── _replay_chat_completion_client.py
        │   │   │       └── semantic_kernel
        │   │   │       │   ├── __init__.py
        │   │   │       │   └── _sk_chat_completion_adapter.py
        │   │   │   ├── py.typed
        │   │   │   ├── runtimes
        │   │   │       ├── __init__.py
        │   │   │       └── grpc
        │   │   │       │   ├── __init__.py
        │   │   │       │   ├── _constants.py
        │   │   │       │   ├── _type_helpers.py
        │   │   │       │   ├── _utils.py
        │   │   │       │   ├── _worker_runtime.py
        │   │   │       │   ├── _worker_runtime_host.py
        │   │   │       │   ├── _worker_runtime_host_servicer.py
        │   │   │       │   └── protos
        │   │   │       │       ├── __init__.py
        │   │   │       │       ├── agent_worker_pb2.py
        │   │   │       │       ├── agent_worker_pb2.pyi
        │   │   │       │       ├── agent_worker_pb2_grpc.py
        │   │   │       │       ├── agent_worker_pb2_grpc.pyi
        │   │   │       │       ├── cloudevent_pb2.py
        │   │   │       │       ├── cloudevent_pb2.pyi
        │   │   │       │       ├── cloudevent_pb2_grpc.py
        │   │   │       │       └── cloudevent_pb2_grpc.pyi
        │   │   │   ├── teams
        │   │   │       ├── __init__.py
        │   │   │       └── magentic_one.py
        │   │   │   ├── tools
        │   │   │       ├── azure
        │   │   │       │   ├── __init__.py
        │   │   │       │   ├── _ai_search.py
        │   │   │       │   └── _config.py
        │   │   │       ├── code_execution
        │   │   │       │   ├── __init__.py
        │   │   │       │   └── _code_execution.py
        │   │   │       ├── graphrag
        │   │   │       │   ├── __init__.py
        │   │   │       │   ├── _config.py
        │   │   │       │   ├── _global_search.py
        │   │   │       │   └── _local_search.py
        │   │   │       ├── http
        │   │   │       │   ├── __init__.py
        │   │   │       │   └── _http_tool.py
        │   │   │       ├── langchain
        │   │   │       │   ├── __init__.py
        │   │   │       │   └── _langchain_adapter.py
        │   │   │       ├── mcp
        │   │   │       │   ├── __init__.py
        │   │   │       │   ├── _actor.py
        │   │   │       │   ├── _base.py
        │   │   │       │   ├── _config.py
        │   │   │       │   ├── _factory.py
        │   │   │       │   ├── _session.py
        │   │   │       │   ├── _sse.py
        │   │   │       │   ├── _stdio.py
        │   │   │       │   ├── _streamable_http.py
        │   │   │       │   └── _workbench.py
        │   │   │       └── semantic_kernel
        │   │   │       │   ├── __init__.py
        │   │   │       │   └── _kernel_function_from_tool.py
        │   │   │   └── ui
        │   │   │       ├── __init__.py
        │   │   │       └── _rich_console.py
        │   ├── test_filesurfer_agent.html
        │   └── tests
        │   │   ├── __init__.py
        │   │   ├── agents
        │   │       └── test_openai_agent_builtin_tool_validation.py
        │   │   ├── cache_store
        │   │       ├── test_diskcache_store.py
        │   │       └── test_redis_store.py
        │   │   ├── code_executors
        │   │       ├── test_aca_dynamic_sessions.py
        │   │       ├── test_aca_user_defined_functions.py
        │   │       ├── test_commandline_code_executor.py
        │   │       ├── test_docker_commandline_code_executor.py
        │   │       ├── test_docker_jupyter_code_executor.py
        │   │       ├── test_jupyter_code_executor.py
        │   │       └── test_user_defined_functions.py
        │   │   ├── conftest.py
        │   │   ├── mcp_server_comprehensive.py
        │   │   ├── memory
        │   │       ├── test_chroma_memory.py
        │   │       ├── test_mem0.py
        │   │       └── test_text_canvas_memory.py
        │   │   ├── models
        │   │       ├── test_anthropic_model_client.py
        │   │       ├── test_azure_ai_model_client.py
        │   │       ├── test_chat_completion_cache.py
        │   │       ├── test_llama_cpp_model_client.py
        │   │       ├── test_ollama_chat_completion_client.py
        │   │       ├── test_openai_model_client.py
        │   │       ├── test_reply_chat_completion_client.py
        │   │       ├── test_sk_chat_completion_adapter.py
        │   │       └── test_utils.py
        │   │   ├── protos
        │   │       ├── serialization_test_pb2.py
        │   │       ├── serialization_test_pb2.pyi
        │   │       ├── serialization_test_pb2_grpc.py
        │   │       └── serialization_test_pb2_grpc.pyi
        │   │   ├── task_centric_memory
        │   │       ├── configs
        │   │       │   ├── demonstration.yaml
        │   │       │   ├── self_teaching.yaml
        │   │       │   └── teachability.yaml
        │   │       ├── data_files
        │   │       │   ├── insights
        │   │       │   │   ├── add_topic.yaml
        │   │       │   │   ├── cell_towers_2_demo.yaml
        │   │       │   │   └── liar_advice.yaml
        │   │       │   └── tasks
        │   │       │   │   ├── 100_vampires.yaml
        │   │       │   │   ├── 10_liars.yaml
        │   │       │   │   ├── autogen_package.yaml
        │   │       │   │   ├── cell_towers_1.yaml
        │   │       │   │   └── cell_towers_2.yaml
        │   │       ├── sessions
        │   │       │   ├── demonstration
        │   │       │   │   └── session.json
        │   │       │   ├── self_teaching
        │   │       │   │   └── session.json
        │   │       │   └── teachability
        │   │       │   │   └── session.json
        │   │       ├── test_chat_completion_client_recorder.py
        │   │       ├── test_learning_from_demonstration.py
        │   │       ├── test_self_teaching.py
        │   │       ├── test_teachability.py
        │   │       └── utils.py
        │   │   ├── test_azure_ai_agent.py
        │   │   ├── test_filesurfer_agent.py
        │   │   ├── test_openai_agent.py
        │   │   ├── test_openai_assistant_agent.py
        │   │   ├── test_playwright_controller.py
        │   │   ├── test_websurfer_agent.py
        │   │   ├── test_worker_runtime.py
        │   │   └── tools
        │   │       ├── __init__.py
        │   │       ├── azure
        │   │           ├── conftest.py
        │   │           ├── test_ai_search_config.py
        │   │           └── test_ai_search_tool.py
        │   │       ├── graphrag
        │   │           ├── __init__.py
        │   │           ├── conftest.py
        │   │           └── test_graphrag_tools.py
        │   │       ├── http
        │   │           ├── __init__.py
        │   │           ├── conftest.py
        │   │           └── test_http_tool.py
        │   │       ├── test_langchain_tools.py
        │   │       ├── test_mcp_actor.py
        │   │       ├── test_mcp_tools.py
        │   │       ├── test_mcp_workbench_features.py
        │   │       ├── test_mcp_workbench_model_client.py
        │   │       ├── test_mcp_workbench_overrides.py
        │   │       ├── test_mcp_workbench_warnings_and_errors.py
        │   │       └── test_python_code_executor_tool.py
        ├── autogen-magentic-one
        │   ├── LICENSE-CODE
        │   └── README.md
        ├── autogen-studio
        │   ├── .devcontainer
        │   │   ├── devcontainer.json
        │   │   └── post-create-command.sh
        │   ├── .gitignore
        │   ├── Dockerfile
        │   ├── LICENSE-CODE
        │   ├── MANIFEST.in
        │   ├── README.md
        │   ├── autogenstudio
        │   │   ├── __init__.py
        │   │   ├── cli.py
        │   │   ├── database
        │   │   │   ├── __init__.py
        │   │   │   ├── db_manager.py
        │   │   │   └── schema_manager.py
        │   │   ├── datamodel
        │   │   │   ├── __init__.py
        │   │   │   ├── db.py
        │   │   │   ├── eval.py
        │   │   │   └── types.py
        │   │   ├── eval
        │   │   │   ├── __init__.py
        │   │   │   ├── judges.py
        │   │   │   ├── orchestrator.py
        │   │   │   └── runners.py
        │   │   ├── gallery
        │   │   │   ├── __init__.py
        │   │   │   ├── builder.py
        │   │   │   └── tools
        │   │   │   │   ├── __init__.py
        │   │   │   │   ├── bing_search.py
        │   │   │   │   ├── calculator.py
        │   │   │   │   ├── fetch_webpage.py
        │   │   │   │   ├── generate_image.py
        │   │   │   │   └── google_search.py
        │   │   ├── lite
        │   │   │   ├── __init__.py
        │   │   │   └── studio.py
        │   │   ├── mcp
        │   │   │   ├── callbacks.py
        │   │   │   ├── client.py
        │   │   │   ├── utils.py
        │   │   │   └── wsbridge.py
        │   │   ├── teammanager
        │   │   │   ├── __init__.py
        │   │   │   └── teammanager.py
        │   │   ├── utils
        │   │   │   ├── __init__.py
        │   │   │   └── utils.py
        │   │   ├── validation
        │   │   │   ├── __init__.py
        │   │   │   ├── component_test_service.py
        │   │   │   └── validation_service.py
        │   │   ├── version.py
        │   │   └── web
        │   │   │   ├── __init__.py
        │   │   │   ├── app.py
        │   │   │   ├── auth
        │   │   │       ├── __init__.py
        │   │   │       ├── authroutes.py
        │   │   │       ├── dependencies.py
        │   │   │       ├── exceptions.py
        │   │   │       ├── manager.py
        │   │   │       ├── middleware.py
        │   │   │       ├── models.py
        │   │   │       ├── providers.py
        │   │   │       └── wsauth.py
        │   │   │   ├── config.py
        │   │   │   ├── deps.py
        │   │   │   ├── initialization.py
        │   │   │   ├── managers
        │   │   │       ├── __init__.py
        │   │   │       ├── connection.py
        │   │   │       └── run_context.py
        │   │   │   ├── routes
        │   │   │       ├── __init__.py
        │   │   │       ├── gallery.py
        │   │   │       ├── mcp.py
        │   │   │       ├── runs.py
        │   │   │       ├── sessions.py
        │   │   │       ├── settingsroute.py
        │   │   │       ├── teams.py
        │   │   │       ├── validation.py
        │   │   │       └── ws.py
        │   │   │   └── serve.py
        │   ├── docs
        │   │   └── ags_screen.png
        │   ├── frontend
        │   │   ├── .env.default
        │   │   ├── .gitignore
        │   │   ├── README.md
        │   │   ├── gatsby-browser.js
        │   │   ├── gatsby-config.ts
        │   │   ├── gatsby-ssr.tsx
        │   │   ├── package.json
        │   │   ├── postcss.config.js
        │   │   ├── src
        │   │   │   ├── auth
        │   │   │   │   ├── api.ts
        │   │   │   │   ├── context.tsx
        │   │   │   │   └── protected.tsx
        │   │   │   ├── components
        │   │   │   │   ├── contentheader.tsx
        │   │   │   │   ├── footer.tsx
        │   │   │   │   ├── header.tsx
        │   │   │   │   ├── icons.tsx
        │   │   │   │   ├── layout.tsx
        │   │   │   │   ├── shared
        │   │   │   │   │   ├── AddComponentDropdown.tsx
        │   │   │   │   │   ├── README.md
        │   │   │   │   │   └── index.ts
        │   │   │   │   ├── sidebar.tsx
        │   │   │   │   ├── types
        │   │   │   │   │   ├── app.ts
        │   │   │   │   │   ├── component-templates.ts
        │   │   │   │   │   ├── datamodel.ts
        │   │   │   │   │   └── guards.ts
        │   │   │   │   ├── utils
        │   │   │   │   │   ├── baseapi.ts
        │   │   │   │   │   ├── security-utils.ts
        │   │   │   │   │   └── utils.ts
        │   │   │   │   └── views
        │   │   │   │   │   ├── atoms.tsx
        │   │   │   │   │   ├── deploy
        │   │   │   │   │       ├── guides
        │   │   │   │   │       │   ├── docker.tsx
        │   │   │   │   │       │   ├── guides.tsx
        │   │   │   │   │       │   └── python.tsx
        │   │   │   │   │       ├── manager.tsx
        │   │   │   │   │       ├── sidebar.tsx
        │   │   │   │   │       └── types.tsx
        │   │   │   │   │   ├── gallery
        │   │   │   │   │       ├── api.ts
        │   │   │   │   │       ├── create-modal.tsx
        │   │   │   │   │       ├── default_gallery.json
        │   │   │   │   │       ├── detail.tsx
        │   │   │   │   │       ├── manager.tsx
        │   │   │   │   │       ├── sidebar.tsx
        │   │   │   │   │       ├── store.tsx
        │   │   │   │   │       ├── types.ts
        │   │   │   │   │       └── utils.ts
        │   │   │   │   │   ├── labs
        │   │   │   │   │       ├── labs
        │   │   │   │   │       │   ├── api.ts
        │   │   │   │   │       │   ├── component.tsx
        │   │   │   │   │       │   ├── guides.tsx
        │   │   │   │   │       │   └── tool.tsx
        │   │   │   │   │       ├── manager.tsx
        │   │   │   │   │       ├── sidebar.tsx
        │   │   │   │   │       └── types.tsx
        │   │   │   │   │   ├── markdown.tsx
        │   │   │   │   │   ├── mcp
        │   │   │   │   │       ├── api.ts
        │   │   │   │   │       ├── create-modal.tsx
        │   │   │   │   │       ├── detail.tsx
        │   │   │   │   │       ├── index.ts
        │   │   │   │   │       ├── manager.tsx
        │   │   │   │   │       ├── sidebar.tsx
        │   │   │   │   │       └── types.ts
        │   │   │   │   │   ├── monaco.tsx
        │   │   │   │   │   ├── playground
        │   │   │   │   │       ├── api.ts
        │   │   │   │   │       ├── chat
        │   │   │   │   │       │   ├── agentflow
        │   │   │   │   │       │   │   ├── agentflow.tsx
        │   │   │   │   │       │   │   ├── agentnode.tsx
        │   │   │   │   │       │   │   ├── edge.tsx
        │   │   │   │   │       │   │   ├── edgemessagemodal.tsx
        │   │   │   │   │       │   │   └── toolbar.tsx
        │   │   │   │   │       │   ├── chat.tsx
        │   │   │   │   │       │   ├── chatinput.tsx
        │   │   │   │   │       │   ├── inputrequest.tsx
        │   │   │   │   │       │   ├── logrenderer.tsx
        │   │   │   │   │       │   ├── rendermessage.tsx
        │   │   │   │   │       │   ├── runview.tsx
        │   │   │   │   │       │   ├── sessiondropdown.tsx
        │   │   │   │   │       │   └── types.ts
        │   │   │   │   │       ├── editor.tsx
        │   │   │   │   │       ├── manager.tsx
        │   │   │   │   │       ├── newsession.tsx
        │   │   │   │   │       ├── sidebar.tsx
        │   │   │   │   │       └── types.ts
        │   │   │   │   │   ├── settings
        │   │   │   │   │       ├── api.ts
        │   │   │   │   │       ├── manager.tsx
        │   │   │   │   │       ├── sidebar.tsx
        │   │   │   │   │       ├── store.tsx
        │   │   │   │   │       ├── types.tsx
        │   │   │   │   │       └── view
        │   │   │   │   │       │   ├── environment.tsx
        │   │   │   │   │       │   ├── modelconfig.tsx
        │   │   │   │   │       │   ├── panel.tsx
        │   │   │   │   │       │   └── ui.tsx
        │   │   │   │   │   └── teambuilder
        │   │   │   │   │       ├── api.ts
        │   │   │   │   │       ├── builder
        │   │   │   │   │           ├── builder.css
        │   │   │   │   │           ├── builder.tsx
        │   │   │   │   │           ├── component-editor
        │   │   │   │   │           │   ├── component-editor.tsx
        │   │   │   │   │           │   ├── detailgroup.tsx
        │   │   │   │   │           │   ├── fields
        │   │   │   │   │           │   │   ├── agent-fields.tsx
        │   │   │   │   │           │   │   ├── fields.tsx
        │   │   │   │   │           │   │   ├── model-fields.tsx
        │   │   │   │   │           │   │   ├── team-fields.tsx
        │   │   │   │   │           │   │   ├── termination-fields.tsx
        │   │   │   │   │           │   │   ├── tool-fields.tsx
        │   │   │   │   │           │   │   └── workbench
        │   │   │   │   │           │   │   │   ├── elicitation-dialog.tsx
        │   │   │   │   │           │   │   │   ├── index.ts
        │   │   │   │   │           │   │   │   ├── mcp-capabilities-panel.tsx
        │   │   │   │   │           │   │   │   ├── mcp-prompts-tab.tsx
        │   │   │   │   │           │   │   │   ├── mcp-resources-tab.tsx
        │   │   │   │   │           │   │   │   ├── mcp-tools-tab.tsx
        │   │   │   │   │           │   │   │   ├── tool-card.tsx
        │   │   │   │   │           │   │   │   ├── useMcpWebSocket.ts
        │   │   │   │   │           │   │   │   └── workbench-fields.tsx
        │   │   │   │   │           │   └── testresults.tsx
        │   │   │   │   │           ├── layout-storage.ts
        │   │   │   │   │           ├── library.tsx
        │   │   │   │   │           ├── nodes.tsx
        │   │   │   │   │           ├── store.tsx
        │   │   │   │   │           ├── testdrawer.tsx
        │   │   │   │   │           ├── toolbar.tsx
        │   │   │   │   │           ├── types.ts
        │   │   │   │   │           ├── utils.ts
        │   │   │   │   │           └── validationerrors.tsx
        │   │   │   │   │       ├── manager.tsx
        │   │   │   │   │       ├── sidebar.tsx
        │   │   │   │   │       └── types.ts
        │   │   │   ├── hooks
        │   │   │   │   ├── provider.tsx
        │   │   │   │   └── store.tsx
        │   │   │   ├── images
        │   │   │   │   ├── icon.png
        │   │   │   │   └── landing
        │   │   │   │   │   ├── nodata.svg
        │   │   │   │   │   └── welcome.svg
        │   │   │   ├── index.d.ts
        │   │   │   ├── pages
        │   │   │   │   ├── 404.tsx
        │   │   │   │   ├── build.tsx
        │   │   │   │   ├── callback.tsx
        │   │   │   │   ├── deploy.tsx
        │   │   │   │   ├── gallery.tsx
        │   │   │   │   ├── index.tsx
        │   │   │   │   ├── labs.tsx
        │   │   │   │   ├── lite.tsx
        │   │   │   │   ├── login.tsx
        │   │   │   │   ├── mcp.tsx
        │   │   │   │   └── settings.tsx
        │   │   │   └── styles
        │   │   │   │   └── global.css
        │   │   ├── static
        │   │   │   └── images
        │   │   │   │   └── bg
        │   │   │   │       └── layeredbg.svg
        │   │   ├── tailwind.config.js
        │   │   ├── tsconfig.json
        │   │   └── yarn.lock
        │   ├── notebooks
        │   │   ├── team.json
        │   │   ├── travel_team.json
        │   │   └── tutorial.ipynb
        │   ├── pyproject.toml
        │   ├── requirements.txt
        │   ├── setup.py
        │   └── tests
        │   │   ├── __init__.py
        │   │   ├── mcp
        │   │       ├── test_mcp_callbacks.py
        │   │       ├── test_mcp_client.py
        │   │       ├── test_mcp_integration.py
        │   │       ├── test_mcp_websocket.py
        │   │       └── test_mcp_wsbridge.py
        │   │   ├── test_datamodel_types.py
        │   │   ├── test_db_manager.py
        │   │   ├── test_lite_studio.py
        │   │   └── test_team_manager.py
        ├── autogen-test-utils
        │   ├── LICENSE-CODE
        │   ├── README.md
        │   ├── pyproject.toml
        │   ├── src
        │   │   └── autogen_test_utils
        │   │   │   ├── __init__.py
        │   │   │   ├── py.typed
        │   │   │   └── telemetry_test_utils.py
        │   └── tests
        │   │   └── test.py
        ├── component-schema-gen
        │   ├── LICENSE-CODE
        │   ├── README.md
        │   ├── pyproject.toml
        │   └── src
        │   │   └── component_schema_gen
        │   │       ├── __init__.py
        │   │       ├── __main__.py
        │   │       └── py.typed
        ├── magentic-one-cli
        │   ├── LICENSE-CODE
        │   ├── README.md
        │   ├── pyproject.toml
        │   └── src
        │   │   └── magentic_one_cli
        │   │       ├── __init__.py
        │   │       ├── __main__.py
        │   │       ├── _m1.py
        │   │       └── py.typed
        └── pyautogen
        │   ├── LICENSE-CODE
        │   ├── README.md
        │   ├── pyproject.toml
        │   └── src
        │       └── pyautogen
        │           └── __init__.py
    ├── pyproject.toml
    ├── run_task_in_pkgs_if_exist.py
    ├── samples
        ├── agentchat_azure_postgresql
        │   └── README.md
        ├── agentchat_chainlit
        │   ├── .gitignore
        │   ├── README.md
        │   ├── app_agent.py
        │   ├── app_team.py
        │   ├── app_team_user_proxy.py
        │   ├── model_config.yaml
        │   └── model_config_template.yaml
        ├── agentchat_chess_game
        │   ├── .gitignore
        │   ├── README.md
        │   ├── main.py
        │   └── model_config_template.yaml
        ├── agentchat_fastapi
        │   ├── .gitignore
        │   ├── README.md
        │   ├── app_agent.html
        │   ├── app_agent.py
        │   ├── app_team.html
        │   ├── app_team.py
        │   └── model_config_template.yaml
        ├── agentchat_graphrag
        │   ├── .gitignore
        │   ├── README.md
        │   ├── app.py
        │   ├── model_config_template.yaml
        │   ├── prompts
        │   │   ├── community_report.txt
        │   │   ├── entity_extraction.txt
        │   │   └── summarize_descriptions.txt
        │   ├── requirements.txt
        │   └── settings.yaml
        ├── agentchat_streamlit
        │   ├── .gitignore
        │   ├── README.md
        │   ├── agent.py
        │   └── main.py
        ├── core_async_human_in_the_loop
        │   ├── .gitignore
        │   ├── README.md
        │   ├── main.py
        │   └── model_config_template.yml
        ├── core_chainlit
        │   ├── .gitignore
        │   ├── README.md
        │   ├── SimpleAssistantAgent.py
        │   ├── app_agent.py
        │   ├── app_team.py
        │   └── model_config_template.yaml
        ├── core_chess_game
        │   ├── .gitignore
        │   ├── README.md
        │   ├── main.py
        │   └── model_config_template.yml
        ├── core_distributed-group-chat
        │   ├── .gitignore
        │   ├── README.md
        │   ├── _agents.py
        │   ├── _types.py
        │   ├── _utils.py
        │   ├── config.yaml
        │   ├── public
        │   │   ├── avatars
        │   │   │   ├── editor.png
        │   │   │   ├── group_chat_manager.png
        │   │   │   ├── user.png
        │   │   │   └── writer.png
        │   │   ├── favicon.png
        │   │   └── logo.png
        │   ├── run.sh
        │   ├── run_editor_agent.py
        │   ├── run_group_chat_manager.py
        │   ├── run_host.py
        │   ├── run_ui.py
        │   └── run_writer_agent.py
        ├── core_grpc_worker_runtime
        │   ├── agents.py
        │   ├── run_cascading_publisher.py
        │   ├── run_cascading_worker.py
        │   ├── run_host.py
        │   ├── run_worker_pub_sub.py
        │   └── run_worker_rpc.py
        ├── core_semantic_router
        │   ├── README.md
        │   ├── _agents.py
        │   ├── _semantic_router_agent.py
        │   ├── _semantic_router_components.py
        │   ├── run_host.py
        │   └── run_semantic_router.py
        ├── core_streaming_handoffs_fastapi
        │   ├── .gitignore
        │   ├── README.md
        │   ├── agent_base.py
        │   ├── agent_user.py
        │   ├── app.py
        │   ├── chat_history
        │   │   └── history-wile_e_coyote_1.json
        │   ├── model_config_template.yaml
        │   ├── models.py
        │   ├── requirements.txt
        │   ├── static
        │   │   └── index.html
        │   ├── tools.py
        │   ├── tools_delegate.py
        │   └── topics.py
        ├── core_streaming_response_fastapi
        │   ├── .gitignore
        │   ├── README.md
        │   ├── app.py
        │   └── model_config_template.yaml
        ├── core_xlang_hello_python_agent
        │   ├── README.md
        │   ├── hello_python_agent.py
        │   ├── protos
        │   │   ├── __init__.py
        │   │   ├── agent_events_pb2.py
        │   │   ├── agent_events_pb2.pyi
        │   │   ├── agent_events_pb2_grpc.py
        │   │   └── agent_events_pb2_grpc.pyi
        │   └── user_input.py
        ├── gitty
        │   ├── .python-version
        │   ├── LICENSE
        │   ├── README.md
        │   ├── pyproject.toml
        │   ├── src
        │   │   └── gitty
        │   │   │   ├── __init__.py
        │   │   │   ├── __main__.py
        │   │   │   ├── _config.py
        │   │   │   ├── _db.py
        │   │   │   ├── _github.py
        │   │   │   └── _gitty.py
        │   └── uv.lock
        └── task_centric_memory
        │   ├── README.md
        │   ├── chat_with_teachable_agent.py
        │   ├── configs
        │       ├── demonstration.yaml
        │       ├── retrieval.yaml
        │       ├── self_teaching.yaml
        │       └── teachability.yaml
        │   ├── data_files
        │       ├── insights
        │       │   ├── add_topic.yaml
        │       │   ├── cell_towers_2_demo.yaml
        │       │   └── liar_advice.yaml
        │       └── tasks
        │       │   ├── 100_vampires.yaml
        │       │   ├── 10_liars.yaml
        │       │   ├── autogen_package.yaml
        │       │   ├── cell_towers_1.yaml
        │       │   └── cell_towers_2.yaml
        │   ├── eval_learning_from_demonstration.py
        │   ├── eval_retrieval.py
        │   ├── eval_self_teaching.py
        │   ├── eval_teachability.py
        │   └── utils.py
    ├── shared_tasks.toml
    ├── templates
        └── new-package
        │   ├── cookiecutter.json
        │   ├── hooks
        │       ├── post_gen_project.py
        │       └── pre_gen_project.py
        │   └── {{cookiecutter.package_name}}
        │       ├── LICENSE-CODE
        │       ├── README.md
        │       ├── pyproject.toml
        │       ├── src
        │           └── {{cookiecutter.__project_slug}}
        │           │   ├── __init__.py
        │           │   └── py.typed
        │       └── tests
        │           └── test_example.py
    └── uv.lock


/.devcontainer/Dockerfile:
--------------------------------------------------------------------------------
1 | # Note: You can use any Debian/Ubuntu based image you want.
2 | FROM mcr.microsoft.com/devcontainers/base:ubuntu
3 | 
4 | # [Optional] Uncomment this section to install additional OS packages.
5 | # RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
6 | #     && apt-get -y install --no-install-recommends <your-package-list-here>
7 | 


--------------------------------------------------------------------------------
/.devcontainer/startup.sh:
--------------------------------------------------------------------------------
 1 | #!/bin/bash
 2 | 
 3 | # dotnet setup
 4 | dotnet workload update
 5 | dotnet dev-certs https --trust
 6 | 
 7 | # python setup
 8 | pushd python
 9 | pip install uv
10 | uv sync
11 | source .venv/bin/activate
12 | echo "export PATH=$PATH" >> ~/.bashrc
13 | popd
14 | 


--------------------------------------------------------------------------------
/.github/ISSUE_TEMPLATE/config.yml:
--------------------------------------------------------------------------------
1 | blank_issues_enabled: false
2 | contact_links:
3 |   - name: 💬 Questions or general help
4 |     url: https://github.com/microsoft/autogen/discussions
5 |     about: Please ask and answer questions here.
6 |   - name: 💡 Suggest a new feature
7 |     url: https://github.com/microsoft/autogen/discussions/categories/feature-suggestions
8 |     about: Please suggest new features here and once the feature is accepted a maintainer will create an issue.
9 | 


--------------------------------------------------------------------------------
/.github/workflows/issue-user-responded.yml:
--------------------------------------------------------------------------------
 1 | name: Remove awaiting-op-response label if op responded
 2 | on:
 3 |   issue_comment:
 4 |     types: [created]
 5 | jobs:
 6 |   label_issues:
 7 |     runs-on: ubuntu-latest
 8 |     permissions:
 9 |       issues: write
10 |       pull-requests: write
11 |     steps:
12 |       - run: gh issue edit "$NUMBER" --remove-label "$LABELS"
13 |         if: ${{ github.event.comment.user.login == github.event.issue.user.login && contains(github.event.issue.labels.*.name, 'awaiting-op-response') }}
14 |         env:
15 |           GH_TOKEN: ${{ secrets.GITHUB_TOKEN }}
16 |           GH_REPO: ${{ github.repository }}
17 |           NUMBER: ${{ github.event.issue.number }}
18 |           LABELS: awaiting-op-response
19 | 


--------------------------------------------------------------------------------
/.github/workflows/lfs-check.yml:
--------------------------------------------------------------------------------
 1 | name: "Git LFS Check"
 2 | 
 3 | on: pull_request
 4 | permissions: {}
 5 | jobs:
 6 |   lfs-check:
 7 |     runs-on: ubuntu-latest
 8 |     steps:
 9 |       - name: Checkout
10 |         uses: actions/checkout@v4
11 |         with:
12 |           lfs: true
13 |       - name: "Check Git LFS files for consistency, if you see error like 'pointer: unexpectedGitObject ... should have been a pointer but was not', please install Git LFS locally, delete the problematic file, and then add it back again. This ensures it's properly tracked."
14 |         run: |
15 |           git lfs fsck
16 | 


--------------------------------------------------------------------------------
/CODE_OF_CONDUCT.md:
--------------------------------------------------------------------------------
 1 | # Microsoft Open Source Code of Conduct
 2 | 
 3 | This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
 4 | 
 5 | Resources:
 6 | 
 7 | - [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/)
 8 | - [Microsoft Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/)
 9 | - Contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with questions or concerns
10 | 


--------------------------------------------------------------------------------
/SUPPORT.md:
--------------------------------------------------------------------------------
 1 | # Support
 2 | 
 3 | ## How to file issues and get help
 4 | 
 5 | This project uses [GitHub Issues](https://github.com/microsoft/autogen/issues)
 6 | to track bugs and feature requests. Please search the existing
 7 | issues before filing new issues to avoid duplicates.  For new issues, file your bug or
 8 | feature request as a new Issue.
 9 | 
10 | For help and questions about using this project, please use
11 | [GitHub Discussion](https://github.com/microsoft/autogen/discussions).
12 | Follow [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/)
13 | when participating in the forum.
14 | 
15 | ## Microsoft Support Policy
16 | 
17 | Support for this project is limited to the resources listed above.
18 | 


--------------------------------------------------------------------------------
/autogen-landing.jpg:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:149a1ab7bec4917c445992c0bff2d4402cb194207a03d4bec573d74d52aac5e8
3 | size 269405
4 | 


--------------------------------------------------------------------------------
/codecov.yml:
--------------------------------------------------------------------------------
1 | coverage:
2 |   status:
3 |     project: off
4 | 


--------------------------------------------------------------------------------
/docs/design/readme.md:
--------------------------------------------------------------------------------
1 | # Docs
2 | 
3 | You can find the project documentation [here](https://microsoft.github.io/autogen/dev/).
4 | 


--------------------------------------------------------------------------------
/docs/dotnet/.gitignore:
--------------------------------------------------------------------------------
 1 | ###############
 2 | #    folder   #
 3 | ###############
 4 | /**/DROP/
 5 | /**/TEMP/
 6 | /**/packages/
 7 | /**/bin/
 8 | /**/obj/
 9 | 
10 | # build artifacts for web
11 | _site/
12 | api/
13 | 


--------------------------------------------------------------------------------
/docs/dotnet/README.md:
--------------------------------------------------------------------------------
 1 | # How to build and run the website
 2 | 
 3 | ## Prerequisites
 4 | 
 5 | - dotnet 8.0 or later
 6 | 
 7 | ## Build
 8 | 
 9 | Firstly, go to autogen/dotnet folder and run the following command to build the website:
10 | 
11 | ```bash
12 | dotnet tool restore
13 | dotnet tool run docfx ../docs/dotnet/docfx.json --serve
14 | ```
15 | 
16 | After the command is executed, you can open your browser and navigate to `http://localhost:8080` to view the website.
17 | 


--------------------------------------------------------------------------------
/docs/dotnet/core/differences-from-python.md:
--------------------------------------------------------------------------------
1 | # Differences from Python
2 | 
3 | ## Publishing to a topic that an agent is also subscribed to
4 | 
5 | > [!NOTE]
6 | > TLDR; Default behavior is identical.
7 | 
8 | When an agent publishes a message to a topic to which it also listens, the message will not be received by the agent that sent it. This is also the behavior in the Python runtime. However to support previous usage, in @Microsoft.AutoGen.Core.InProcessRuntime, you can set the @Microsoft.AutoGen.Core.InProcessRuntime.DeliverToSelf property to true in the TopicSubscription attribute to allow an agent to receive messages it sends.
9 | 


--------------------------------------------------------------------------------
/docs/dotnet/core/toc.yml:
--------------------------------------------------------------------------------
 1 | - name: Overview
 2 |   href: index.md
 3 | - name: Installation
 4 |   href: installation.md
 5 | - name: Tutorial
 6 |   href: tutorial.md
 7 | - name: Differences from Python
 8 |   href: differences-from-python.md
 9 | - name: Protobuf message types
10 |   href: protobuf-message-types.md
11 | 


--------------------------------------------------------------------------------
/docs/dotnet/images/favicon.ico:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/docs/dotnet/images/favicon.ico


--------------------------------------------------------------------------------
/docs/dotnet/template/public/main.js:
--------------------------------------------------------------------------------
1 | export default {
2 |     iconLinks: [
3 |       {
4 |         icon: 'github',
5 |         href: 'https://github.com/microsoft/autogen',
6 |         title: 'GitHub'
7 |       }
8 |     ]
9 |   }


--------------------------------------------------------------------------------
/docs/dotnet/toc.yml:
--------------------------------------------------------------------------------
1 | - name: Core
2 |   href: core/
3 | 
4 | - name: API Reference
5 |   href: api/
6 | 
7 | - name: Python⤴
8 |   href: https://microsoft.github.io/autogen/
9 | 


--------------------------------------------------------------------------------
/dotnet/.config/dotnet-tools.json:
--------------------------------------------------------------------------------
 1 | {
 2 |   "version": 1,
 3 |   "isRoot": true,
 4 |   "tools": {
 5 |     "dotnet-repl": {
 6 |       "version": "0.1.205",
 7 |       "commands": [
 8 |         "dotnet-repl"
 9 |       ],
10 |       "rollForward": true
11 |     },
12 |     "docfx": {
13 |       "version": "2.67.5",
14 |       "commands": [
15 |         "docfx"
16 |       ],
17 |       "rollForward": true
18 |     }
19 |   }
20 | }


--------------------------------------------------------------------------------
/dotnet/AutoGen.v3.ncrunchsolution:
--------------------------------------------------------------------------------
1 | ﻿<SolutionConfiguration>
2 |   <Settings>
3 |     <AllowParallelTestExecution>True</AllowParallelTestExecution>
4 |     <EnableRDI>True</EnableRDI>
5 |     <RdiConfigured>True</RdiConfigured>
6 |     <SolutionConfigured>True</SolutionConfigured>
7 |   </Settings>
8 | </SolutionConfiguration>


--------------------------------------------------------------------------------
/dotnet/Directory.Build.targets:
--------------------------------------------------------------------------------
 1 | <Project>
 2 | 
 3 |   <PropertyGroup>
 4 |     <ReadMePath>$(MSBuildProjectDirectory)\README.md</ReadMePath>
 5 |     <ReadMeExists Condition="Exists('$(ReadMePath)')">true</ReadMeExists>
 6 |     <PackageReadmeFile Condition="'$(PackageReadmeFile)' == '' And '$(ReadMeExists)' == 'true'">README.md</PackageReadmeFile>
 7 |   </PropertyGroup>
 8 | 
 9 |   <ItemGroup Condition="'$(ReadMeExists)' == 'true'">
10 |     <None Include="$(ReadMePath)" Pack="true" PackagePath="\" />
11 |   </ItemGroup>
12 | 
13 | </Project>
14 | 


--------------------------------------------------------------------------------
/dotnet/NuGet.config:
--------------------------------------------------------------------------------
1 | ﻿<?xml version="1.0" encoding="utf-8"?>
2 | <configuration>
3 |   <packageSources>
4 |     <clear />
5 |     <add key="nuget" value="https://api.nuget.org/v3/index.json" />
6 |   </packageSources>
7 |   <disabledPackageSources />
8 | </configuration>


--------------------------------------------------------------------------------
/dotnet/eng/MetaInfo.props:
--------------------------------------------------------------------------------
 1 | <?xml version="1.0" encoding="utf-8"?>
 2 | <Project ToolsVersion="4.0" xmlns="http://schemas.microsoft.com/developer/msbuild/2003">
 3 |     <PropertyGroup>
 4 |         <VersionPrefix>0.4.0</VersionPrefix>
 5 |         <VersionPrefixForAutoGen0_2>0.2.3</VersionPrefixForAutoGen0_2>
 6 |         <Authors>Microsoft</Authors>
 7 |         <PackageProjectUrl>https://microsoft.github.io/autogen-for-net/</PackageProjectUrl>
 8 |         <RepositoryUrl>https://github.com/microsoft/autogen</RepositoryUrl>
 9 |         <RepositoryType>git</RepositoryType>
10 |         <PackageLicenseExpression>MIT</PackageLicenseExpression>
11 |         <PackageRequireLicenseAcceptance>false</PackageRequireLicenseAcceptance>
12 |     </PropertyGroup>
13 | </Project>
14 | 


--------------------------------------------------------------------------------
/dotnet/eng/opensource.snk:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/dotnet/eng/opensource.snk


--------------------------------------------------------------------------------
/dotnet/global.json:
--------------------------------------------------------------------------------
1 | {
2 |   "sdk": {
3 |     "version": "9.0.100",
4 |     "rollForward": "latestFeature"
5 |   }
6 | }
7 | 


--------------------------------------------------------------------------------
/dotnet/nuget/NUGET.md:
--------------------------------------------------------------------------------
1 | ### About AutoGen for .NET
2 | `AutoGen for .NET` is the official .NET SDK for [AutoGen](https://github.com/microsoft/autogen). It enables you to create LLM agents and construct multi-agent workflows with ease. It also provides integration with popular platforms like OpenAI, Semantic Kernel, and LM Studio.
3 | 
4 | ### Gettings started
5 | - Find documents and examples on our [document site](https://microsoft.github.io/autogen-for-net/)
6 | - Report a bug or request a feature by creating a new issue in our [github repo](https://github.com/microsoft/autogen)
7 | - Consume the nightly build package from one of the [nightly build feeds](https://microsoft.github.io/autogen-for-net/articles/Installation.html#nighly-build)


--------------------------------------------------------------------------------
/dotnet/nuget/README.md:
--------------------------------------------------------------------------------
 1 | # NuGet Directory
 2 | 
 3 | This directory contains resources and metadata for packaging the AutoGen.NET SDK as a NuGet package.
 4 | 
 5 | ## Files
 6 | 
 7 | - **icon.png**: The icon used for the NuGet package.
 8 | - **NUGET.md**: The readme file displayed on the NuGet package page.
 9 | - **NUGET-PACKAGE.PROPS**: The MSBuild properties file that defines the packaging settings for the NuGet package.
10 | 
11 | ## Purpose
12 | 
13 | The files in this directory are used to configure and build the NuGet package for the AutoGen.NET SDK, ensuring that it includes necessary metadata, documentation, and resources.


--------------------------------------------------------------------------------
/dotnet/nuget/icon.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:02dbf31fea0b92714c80fdc90888da7e96374a1f52c621a939835fd3c876ddcc
3 | size 426084
4 | 


--------------------------------------------------------------------------------
/dotnet/resource/images/background.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:300b7c9d6ba0c23a3e52fbd2e268141ddcca0434a9fb9dcf7e58e7e903d36dcf
3 | size 2126185
4 | 


--------------------------------------------------------------------------------
/dotnet/resource/images/square.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:8323d0b8eceb752e14c29543b2e28bb2fc648ed9719095c31b7708867a4dc918
3 | size 491
4 | 


--------------------------------------------------------------------------------
/dotnet/samples/AgentChat/AutoGen.Anthropic.Sample/Program.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // Program.cs
 3 | 
 4 | namespace AutoGen.Anthropic.Sample;
 5 | 
 6 | internal static class Program
 7 | {
 8 |     public static async Task Main(string[] _)
 9 |     {
10 |         await Anthropic_Agent_With_Prompt_Caching.RunAsync();
11 |     }
12 | }
13 | 


--------------------------------------------------------------------------------
/dotnet/samples/AgentChat/AutoGen.Basic.Sample/CodeSnippet/UserProxyAgentCodeSnippet.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // UserProxyAgentCodeSnippet.cs
 3 | 
 4 | using AutoGen.Core;
 5 | 
 6 | namespace AutoGen.Basic.Sample.CodeSnippet;
 7 | 
 8 | public class UserProxyAgentCodeSnippet
 9 | {
10 |     public async Task CodeSnippet1()
11 |     {
12 |         #region code_snippet_1
13 |         // create a user proxy agent which always ask user for input
14 |         var agent = new UserProxyAgent(
15 |             name: "user",
16 |             humanInputMode: HumanInputMode.ALWAYS);
17 | 
18 |         await agent.SendAsync("hello");
19 |         #endregion code_snippet_1
20 |     }
21 | }
22 | 


--------------------------------------------------------------------------------
/dotnet/samples/AgentChat/AutoGen.Basic.Sample/Example13_OpenAIAgent_JsonMode.cs:
--------------------------------------------------------------------------------
1 | // Copyright (c) Microsoft Corporation. All rights reserved.
2 | // Example13_OpenAIAgent_JsonMode.cs
3 | 
4 | // this example has been moved to https://github.com/microsoft/autogen/blob/main/dotnet/samples/AutoGen.OpenAI.Sample/Use_Json_Mode.cs
5 | 
6 | 


--------------------------------------------------------------------------------
/dotnet/samples/AgentChat/AutoGen.Basic.Sample/Example16_OpenAIChatAgent_ConnectToThirdPartyBackend.cs:
--------------------------------------------------------------------------------
1 | // Copyright (c) Microsoft Corporation. All rights reserved.
2 | // Example16_OpenAIChatAgent_ConnectToThirdPartyBackend.cs
3 | 
4 | // this example has been moved to https://github.com/microsoft/autogen/blob/main/dotnet/samples/AutoGen.OpenAI.Sample/Connect_To_Ollama.cs
5 | 


--------------------------------------------------------------------------------
/dotnet/samples/AgentChat/AutoGen.Basic.Sample/GlobalUsing.cs:
--------------------------------------------------------------------------------
1 | // Copyright (c) Microsoft Corporation. All rights reserved.
2 | // GlobalUsing.cs
3 | 
4 | 


--------------------------------------------------------------------------------
/dotnet/samples/AgentChat/AutoGen.Gemini.Sample/Program.cs:
--------------------------------------------------------------------------------
1 | // Copyright (c) Microsoft Corporation. All rights reserved.
2 | // Program.cs
3 | 
4 | using AutoGen.Gemini.Sample;
5 | 
6 | Image_Chat_With_Vertex_Gemini.RunAsync().Wait();
7 | 


--------------------------------------------------------------------------------
/dotnet/samples/AgentChat/AutoGen.Ollama.Sample/Program.cs:
--------------------------------------------------------------------------------
1 | // Copyright (c) Microsoft Corporation. All rights reserved.
2 | // Program.cs
3 | 
4 | using AutoGen.Ollama.Sample;
5 | 
6 | await Chat_With_LLaVA.RunAsync();
7 | 


--------------------------------------------------------------------------------
/dotnet/samples/AgentChat/AutoGen.OpenAI.Sample/Program.cs:
--------------------------------------------------------------------------------
1 | // Copyright (c) Microsoft Corporation. All rights reserved.
2 | // Program.cs
3 | 
4 | using AutoGen.OpenAI.Sample;
5 | 
6 | Structural_Output.RunAsync().Wait();
7 | 


--------------------------------------------------------------------------------
/dotnet/samples/AgentChat/AutoGen.SemanticKernel.Sample/Program.cs:
--------------------------------------------------------------------------------
1 | // Copyright (c) Microsoft Corporation. All rights reserved.
2 | // Program.cs
3 | 
4 | using AutoGen.SemanticKernel.Sample;
5 | 
6 | await Use_Kernel_Functions_With_Other_Agent.RunAsync();
7 | 


--------------------------------------------------------------------------------
/dotnet/samples/AgentChat/AutoGen.WebAPI.Sample/AutoGen.WebAPI.Sample.csproj:
--------------------------------------------------------------------------------
 1 | ﻿<Project Sdk="Microsoft.NET.Sdk.Web">
 2 | 
 3 |   <PropertyGroup>
 4 |     <TargetFrameworks>$(TestTargetFrameworks)</TargetFrameworks>
 5 |     <ImplicitUsings>enable</ImplicitUsings>
 6 |     <Nullable>enable</Nullable>
 7 |   </PropertyGroup>
 8 | 
 9 |   <ItemGroup>
10 |     <ProjectReference Include="..\..\..\src\AutoGen.WebAPI\AutoGen.WebAPI.csproj" />
11 |   </ItemGroup>
12 | 
13 | </Project>
14 | 


--------------------------------------------------------------------------------
/dotnet/samples/AgentChat/AutoGen.WebAPI.Sample/Properties/launchSettings.json:
--------------------------------------------------------------------------------
 1 | {
 2 |   "profiles": {
 3 |     "AutoGen.WebAPI.Sample": {
 4 |       "commandName": "Project",
 5 |       "launchBrowser": true,
 6 |       "environmentVariables": {
 7 |         "ASPNETCORE_ENVIRONMENT": "Development"
 8 |       },
 9 |       "applicationUrl": "https://localhost:50675;http://localhost:50676"
10 |     }
11 |   }
12 | }


--------------------------------------------------------------------------------
/dotnet/samples/Directory.Build.props:
--------------------------------------------------------------------------------
 1 | <?xml version="1.0" encoding="utf-8"?>
 2 | <Project ToolsVersion="4.0" xmlns="http://schemas.microsoft.com/developer/msbuild/2003">
 3 |   <Import Project="../Directory.Build.props" />
 4 |   <PropertyGroup>
 5 |     <SignAssembly>False</SignAssembly>
 6 |     <AssemblyOriginatorKeyFile></AssemblyOriginatorKeyFile>
 7 |     <PublicKey></PublicKey>
 8 |   </PropertyGroup>
 9 | </Project>
10 | 


--------------------------------------------------------------------------------
/dotnet/samples/GettingStarted/CountMessage.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // CountMessage.cs
 3 | 
 4 | #region snippet_CountMessage
 5 | namespace GettingStartedSample;
 6 | 
 7 | public class CountMessage
 8 | {
 9 |     public int Content { get; set; }
10 | }
11 | #endregion
12 | 


--------------------------------------------------------------------------------
/dotnet/samples/GettingStarted/CountUpdate.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // CountUpdate.cs
 3 | 
 4 | #region snippet_CountUpdate
 5 | namespace GettingStartedSample;
 6 | 
 7 | public class CountUpdate
 8 | {
 9 |     public int NewCount { get; set; }
10 | }
11 | #endregion
12 | 


--------------------------------------------------------------------------------
/dotnet/samples/GettingStarted/GettingStarted.csproj:
--------------------------------------------------------------------------------
 1 | ﻿<Project Sdk="Microsoft.NET.Sdk">
 2 | 
 3 |   <PropertyGroup>
 4 |     <OutputType>Exe</OutputType>
 5 |     <TargetFramework>net8.0</TargetFramework>
 6 |     <RootNamespace>getting_started</RootNamespace>
 7 |     <ImplicitUsings>enable</ImplicitUsings>
 8 |     <Nullable>enable</Nullable>
 9 |   </PropertyGroup>
10 | 
11 |   <ItemGroup>
12 |     <ProjectReference Include="..\..\src\Microsoft.AutoGen\Contracts\Microsoft.AutoGen.Contracts.csproj" />
13 |     <ProjectReference Include="..\..\src\Microsoft.AutoGen\Core\Microsoft.AutoGen.Core.csproj" />
14 |   </ItemGroup>
15 | </Project>
16 | 


--------------------------------------------------------------------------------
/dotnet/samples/GettingStartedGrpc/message.proto:
--------------------------------------------------------------------------------
 1 | syntax = "proto3";
 2 | 
 3 | option csharp_namespace = "GettingStartedGrpcSample.Events";
 4 | 
 5 | message CountMessage {
 6 |     int32 content = 1;
 7 | }
 8 | 
 9 | message CountUpdate {
10 |     int32 new_count = 1;
11 | }
12 | 


--------------------------------------------------------------------------------
/dotnet/samples/Hello/Hello.AppHost/appsettings.Development.json:
--------------------------------------------------------------------------------
 1 | {
 2 |   "Logging": {
 3 |     "LogLevel": {
 4 |       "Default": "Information",
 5 |       "Microsoft.AspNetCore": "Warning",
 6 |       "Aspire.Hosting.ApplicationModel.ResourceNotificationService": "Debug"
 7 |     }
 8 |   }
 9 | }
10 | 


--------------------------------------------------------------------------------
/dotnet/samples/Hello/HelloAIAgents/Properties/launchSettings.json:
--------------------------------------------------------------------------------
 1 | {
 2 |   "profiles": {
 3 |     "HelloAIAgents": {
 4 |       "commandName": "Project",
 5 |       "launchBrowser": true,
 6 |       "environmentVariables": {
 7 |         "ASPNETCORE_ENVIRONMENT": "Development"
 8 |       },
 9 |       "applicationUrl": "https://localhost:53139;http://localhost:53140"
10 |     }
11 |   }
12 | }


--------------------------------------------------------------------------------
/dotnet/samples/Hello/HelloAIAgents/appsettings.json:
--------------------------------------------------------------------------------
1 | {
2 |     "Logging": {
3 |       "LogLevel": {
4 |         "Default": "Warning",
5 |         "Microsoft": "Warning",
6 |         "Microsoft.Orleans": "Warning"
7 |       }
8 |     }
9 |   }


--------------------------------------------------------------------------------
/dotnet/samples/Hello/HelloAgent/Properties/launchSettings.json:
--------------------------------------------------------------------------------
 1 | {
 2 |   "profiles": {
 3 |     "HelloAgent": {
 4 |       "commandName": "Project",
 5 |       "launchBrowser": true,
 6 |       "environmentVariables": {
 7 |         "ASPNETCORE_ENVIRONMENT": "Development"
 8 |       },
 9 |       "applicationUrl": "https://localhost:53113;http://localhost:53114"
10 |     }
11 |   }
12 | }


--------------------------------------------------------------------------------
/dotnet/samples/Hello/HelloAgent/appsettings.json:
--------------------------------------------------------------------------------
1 | {
2 |     "Logging": {
3 |       "LogLevel": {
4 |         "Default": "Warning",
5 |         "Microsoft": "Information",
6 |         "Microsoft.Orleans": "Warning"
7 |       }
8 |     }
9 |   }


--------------------------------------------------------------------------------
/dotnet/samples/Hello/HelloAgentState/Properties/launchSettings.json:
--------------------------------------------------------------------------------
 1 | {
 2 |   "profiles": {
 3 |     "HelloAgentState": {
 4 |       "commandName": "Project",
 5 |       "launchBrowser": true,
 6 |       "environmentVariables": {
 7 |         "ASPNETCORE_ENVIRONMENT": "Development"
 8 |       },
 9 |       "applicationUrl": "https://localhost:53136;http://localhost:53137"
10 |     }
11 |   }
12 | }


--------------------------------------------------------------------------------
/dotnet/samples/Hello/HelloAgentState/appsettings.json:
--------------------------------------------------------------------------------
1 | {
2 |     "Logging": {
3 |       "LogLevel": {
4 |         "Default": "Warning",
5 |         "Microsoft": "Warning",
6 |         "Microsoft.Orleans": "Warning"
7 |       }
8 |     }
9 |   }


--------------------------------------------------------------------------------
/dotnet/samples/Hello/README.md:
--------------------------------------------------------------------------------
 1 | # Multiproject App Host for HelloAgent
 2 | 
 3 | This is a [.NET Aspire](https://learn.microsoft.com/en-us/dotnet/aspire/get-started/aspire-overview) App Host that starts up the HelloAgent project and the agents backend. Once the project starts up you will be able to view the telemetry and logs in the [Aspire Dashboard](https://learn.microsoft.com/en-us/dotnet/aspire/get-started/aspire-dashboard) using the link provided in the console.
 4 | 
 5 | ```shell
 6 | cd Hello.AppHost
 7 | dotnet run
 8 | ```
 9 | 
10 | For more info see the HelloAgent [README](../HelloAgent/README.md).
11 | 


--------------------------------------------------------------------------------
/dotnet/samples/dev-team/DevTeam.AppHost/appsettings.Development.json:
--------------------------------------------------------------------------------
1 | {
2 |   "Logging": {
3 |     "LogLevel": {
4 |       "Default": "Information",
5 |       "Microsoft.AspNetCore": "Warning"
6 |     }
7 |   }
8 | }
9 | 


--------------------------------------------------------------------------------
/dotnet/samples/dev-team/DevTeam.Backend/AiAgent.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // AiAgent.cs
 3 | 
 4 | using Microsoft.AutoGen.Core;
 5 | 
 6 | namespace DevTeam.Agents;
 7 | 
 8 | public class AiAgent<T> : Agent
 9 | {
10 |     public AiAgent(AgentsMetadata eventTypes, ILogger<AiAgent<T>> logger) : base(eventTypes, logger)
11 |     {
12 |     }
13 | 
14 |     protected async Task AddKnowledge(string instruction, string v)
15 |     {
16 |         throw new NotImplementedException();
17 |     }
18 | 
19 |     protected async Task<string> CallFunction(string prompt)
20 |     {
21 |         throw new NotImplementedException();
22 |     }
23 | }
24 | 


--------------------------------------------------------------------------------
/dotnet/samples/dev-team/DevTeam.Backend/Consts.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // Consts.cs
 3 | 
 4 | namespace DevTeam.Backend;
 5 | 
 6 | public class Consts
 7 | {
 8 |     public const string TopicName = "devteam";
 9 | }
10 | 


--------------------------------------------------------------------------------
/dotnet/samples/dev-team/DevTeam.Backend/Models/DevPlan.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // DevPlan.cs
 3 | 
 4 | namespace DevTeam;
 5 | public class DevLeadPlan
 6 | {
 7 |     public required List<StepDescription> Steps { get; set; }
 8 | }
 9 | 
10 | public class StepDescription
11 | {
12 |     public string? Description { get; set; }
13 |     public string? Step { get; set; }
14 |     public List<SubtaskDescription>? Subtasks { get; set; }
15 | }
16 | 
17 | public class SubtaskDescription
18 | {
19 |     public string? Subtask { get; set; }
20 |     public string? Prompt { get; set; }
21 | }
22 | 


--------------------------------------------------------------------------------
/dotnet/samples/dev-team/DevTeam.Backend/Options/GithubOptions.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // GithubOptions.cs
 3 | 
 4 | using System.ComponentModel.DataAnnotations;
 5 | 
 6 | namespace DevTeam.Options;
 7 | public class GithubOptions
 8 | {
 9 |     [Required]
10 |     public required string AppKey { get; set; }
11 |     [Required]
12 |     public int AppId { get; set; }
13 |     [Required]
14 |     public long InstallationId { get; set; }
15 |     [Required]
16 |     public required string WebhookSecret { get; set; }
17 | }
18 | 


--------------------------------------------------------------------------------
/dotnet/samples/dev-team/DevTeam.Backend/Properties/launchSettings.json:
--------------------------------------------------------------------------------
 1 | {
 2 |   "profiles": {
 3 |     "DevTeam.Backend": {
 4 |       "commandName": "Project",
 5 |       "launchBrowser": true,
 6 |       "environmentVariables": {
 7 |         "ASPNETCORE_ENVIRONMENT": "Development"
 8 |       },
 9 |       "applicationUrl": "https://localhost:50672;http://localhost:50674"
10 |     }
11 |   }
12 | }


--------------------------------------------------------------------------------
/dotnet/samples/dev-team/DevTeam.Backend/appsettings.Development.json:
--------------------------------------------------------------------------------
1 | {
2 |   "Logging": {
3 |     "LogLevel": {
4 |       "Default": "Information",
5 |       "Microsoft.AspNetCore": "Warning"
6 |     }
7 |   }
8 | }
9 | 


--------------------------------------------------------------------------------
/dotnet/samples/dev-team/Protos/states.proto:
--------------------------------------------------------------------------------
 1 | syntax = "proto3";
 2 | 
 3 | package devteam;
 4 | 
 5 | option csharp_namespace = "DevTeam";
 6 | 
 7 | 
 8 | message DeveloperState {
 9 |   string understanding = 1;
10 | }
11 | 
12 | message DeveloperLeadState {
13 |   string plan = 1;
14 | }
15 | 
16 | message ProductManagerState {
17 |   string capabilities = 1;
18 | }
19 | 


--------------------------------------------------------------------------------
/dotnet/samples/dev-team/azure.yaml:
--------------------------------------------------------------------------------
1 | # yaml-language-server: $schema=https://raw.githubusercontent.com/Azure/azure-dev/main/schemas/v1.0/azure.yaml.json
2 | 
3 | name: ai-dev-team
4 | services:
5 |   gh-flow:
6 |     project: "./DevTeam.AppHost/DevTeam.AppHost.csproj"
7 |     language: dotnet
8 |     host: containerapp
9 | 


--------------------------------------------------------------------------------
/dotnet/samples/dev-team/docs/images/github-sk-dev-team.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:a5c18db95ff3d7357cd9112e3e8698185d819c796a053b070782d019ff1437c9
3 | size 309649
4 | 


--------------------------------------------------------------------------------
/dotnet/samples/dev-team/docs/images/new-codespace.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:d01b942495de39ee2ab443283cfa22b51de8482710709b984dd21d5907b59a1b
3 | size 27275
4 | 


--------------------------------------------------------------------------------
/dotnet/samples/dev-team/docs/images/overview.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:8de049310295afdeca720b7b289967d8f960998e426c10ccd862b3bcfb81ef0b
3 | size 348879
4 | 


--------------------------------------------------------------------------------
/dotnet/samples/dev-team/docs/images/solution-explorer.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:62294a0181f1f0b5a2cb9dff20cc6911df9df80a1752a2d7bdf22b7615d2fc78
3 | size 60694
4 | 


--------------------------------------------------------------------------------
/dotnet/samples/dev-team/seed-memory/Dockerfile:
--------------------------------------------------------------------------------
 1 | FROM mcr.microsoft.com/dotnet/runtime:7.0 AS base
 2 | WORKDIR /app
 3 | 
 4 | FROM mcr.microsoft.com/dotnet/sdk:7.0 AS build
 5 | WORKDIR /src
 6 | COPY ["util/seed-memory/seed-memory.csproj", "util/seed-memory/"]
 7 | RUN dotnet restore "util/seed-memory/seed-memory.csproj"
 8 | COPY . .
 9 | WORKDIR "/src/util/seed-memory"
10 | RUN dotnet build "seed-memory.csproj" -c Release -o /app/build
11 | 
12 | FROM build AS publish
13 | RUN dotnet publish "seed-memory.csproj" -c Release -o /app/publish /p:UseAppHost=false
14 | 
15 | FROM base AS final
16 | WORKDIR /app
17 | COPY --from=publish /app/publish .
18 | ENTRYPOINT ["dotnet", "seed-memory.dll"]
19 | 


--------------------------------------------------------------------------------
/dotnet/samples/dev-team/seed-memory/README.md:
--------------------------------------------------------------------------------
1 | # TODO


--------------------------------------------------------------------------------
/dotnet/samples/dev-team/seed-memory/azure-well-architected.pdf:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/dotnet/samples/dev-team/seed-memory/azure-well-architected.pdf


--------------------------------------------------------------------------------
/dotnet/samples/dev-team/seed-memory/config/appsettings.template.json:
--------------------------------------------------------------------------------
1 | {
2 |   "serviceType": "AzureOpenAI",
3 |   "serviceId": "",
4 |   "deploymentOrModelId": "",
5 |   "embeddingDeploymentOrModelId": "",
6 |   "endpoint": "",
7 |   "apiKey": "",
8 |   "qdrantEndpoint": ""
9 | }


--------------------------------------------------------------------------------
/dotnet/spelling.dic:
--------------------------------------------------------------------------------
1 | qdrant
2 | orleans
3 | openai
4 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.Anthropic/AutoGen.Anthropic.csproj:
--------------------------------------------------------------------------------
 1 | ﻿<Project Sdk="Microsoft.NET.Sdk">
 2 | 
 3 |   <PropertyGroup>
 4 |     <TargetFrameworks>$(PackageTargetFrameworks)</TargetFrameworks>
 5 |     <RootNamespace>AutoGen.Anthropic</RootNamespace>
 6 |   </PropertyGroup>
 7 | 
 8 |   <Import Project="$(RepoRoot)/nuget/nuget-package.props" />
 9 | 
10 |   <PropertyGroup>
11 |     <!-- NuGet Package Settings -->
12 |     <Title>AutoGen.Anthropic</Title>
13 |     <Description>
14 |       Provide support for consuming Anthropic models in AutoGen
15 |     </Description>
16 |   </PropertyGroup>
17 | 
18 |   <ItemGroup>
19 |     <ProjectReference Include="..\AutoGen.Core\AutoGen.Core.csproj" />
20 |   </ItemGroup>
21 | 
22 | </Project>
23 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.Anthropic/DTO/ErrorResponse.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // ErrorResponse.cs
 3 | 
 4 | using System.Text.Json.Serialization;
 5 | 
 6 | namespace AutoGen.Anthropic.DTO;
 7 | 
 8 | public sealed class ErrorResponse
 9 | {
10 |     [JsonPropertyName("error")]
11 |     public Error? Error { get; set; }
12 | }
13 | 
14 | public sealed class Error
15 | {
16 |     [JsonPropertyName("Type")]
17 |     public string? Type { get; set; }
18 | 
19 |     [JsonPropertyName("message")]
20 |     public string? Message { get; set; }
21 | }
22 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.Anthropic/Utils/AnthropicConstants.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // AnthropicConstants.cs
 3 | 
 4 | namespace AutoGen.Anthropic.Utils;
 5 | 
 6 | public static class AnthropicConstants
 7 | {
 8 |     public static string Endpoint = "https://api.anthropic.com/v1/messages";
 9 | 
10 |     // Models
11 |     public static string Claude3Opus = "claude-3-opus-20240229";
12 |     public static string Claude3Sonnet = "claude-3-sonnet-20240229";
13 |     public static string Claude3Haiku = "claude-3-haiku-20240307";
14 |     public static string Claude35Sonnet = "claude-3-5-sonnet-20240620";
15 | }
16 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.Core/Agent/IStreamingAgent.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // IStreamingAgent.cs
 3 | 
 4 | using System.Collections.Generic;
 5 | using System.Threading;
 6 | 
 7 | namespace AutoGen.Core;
 8 | 
 9 | /// <summary>
10 | /// agent that supports streaming reply
11 | /// </summary>
12 | public interface IStreamingAgent : IAgent
13 | {
14 |     public IAsyncEnumerable<IMessage> GenerateStreamingReplyAsync(
15 |         IEnumerable<IMessage> messages,
16 |         GenerateReplyOptions? options = null,
17 |         CancellationToken cancellationToken = default);
18 | }
19 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.Core/GroupChat/IGroupChat.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // IGroupChat.cs
 3 | 
 4 | using System;
 5 | using System.Collections.Generic;
 6 | using System.Threading;
 7 | using System.Threading.Tasks;
 8 | 
 9 | namespace AutoGen.Core;
10 | 
11 | public interface IGroupChat
12 | {
13 |     /// <summary>
14 |     /// Send an introduction message to the group chat.
15 |     /// </summary>
16 |     void SendIntroduction(IMessage message);
17 | 
18 |     [Obsolete("please use SendIntroduction")]
19 |     void AddInitializeMessage(IMessage message);
20 | 
21 |     Task<IEnumerable<IMessage>> CallAsync(IEnumerable<IMessage>? conversation = null, int maxRound = 10, CancellationToken ct = default);
22 | }
23 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.Core/ILLMConfig.cs:
--------------------------------------------------------------------------------
1 | // Copyright (c) Microsoft Corporation. All rights reserved.
2 | // ILLMConfig.cs
3 | 
4 | namespace AutoGen.Core;
5 | 
6 | public interface ILLMConfig
7 | {
8 | }
9 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.Core/Middleware/MiddlewareContext.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // MiddlewareContext.cs
 3 | 
 4 | using System.Collections.Generic;
 5 | 
 6 | namespace AutoGen.Core;
 7 | 
 8 | public class MiddlewareContext
 9 | {
10 |     public MiddlewareContext(
11 |         IEnumerable<IMessage> messages,
12 |         GenerateReplyOptions? options)
13 |     {
14 |         this.Messages = messages;
15 |         this.Options = options;
16 |     }
17 | 
18 |     /// <summary>
19 |     /// Messages to send to the agent
20 |     /// </summary>
21 |     public IEnumerable<IMessage> Messages { get; }
22 | 
23 |     /// <summary>
24 |     /// Options to generate the reply
25 |     /// </summary>
26 |     public GenerateReplyOptions? Options { get; }
27 | }
28 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.DotnetInteractive/GlobalUsing.cs:
--------------------------------------------------------------------------------
1 | // Copyright (c) Microsoft Corporation. All rights reserved.
2 | // GlobalUsing.cs
3 | 
4 | global using AutoGen.Core;
5 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.DotnetInteractive/RestoreInteractive.config:
--------------------------------------------------------------------------------
1 | <?xml version="1.0" encoding="utf-8"?>
2 | <configuration>
3 | 	<packageSources>
4 | 		<clear />
5 | 		<add key="nuget.org"
6 | 			 value="https://api.nuget.org/v3/index.json" />
7 | 	</packageSources>
8 | 	<disabledPackageSources />
9 | </configuration>


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.DotnetInteractive/dotnet-tools.json:
--------------------------------------------------------------------------------
 1 | {
 2 |   "version": 1,
 3 |   "isRoot": true,
 4 |   "tools": {
 5 |     "Microsoft.dotnet-interactive": {
 6 |       "version": "1.0.522904",
 7 |       "commands": [
 8 |         "dotnet-interactive"
 9 |       ]
10 |     }
11 |   }
12 | }


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.Gemini/IGeminiClient.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // IGeminiClient.cs
 3 | 
 4 | using System.Collections.Generic;
 5 | using System.Threading;
 6 | using System.Threading.Tasks;
 7 | using Google.Cloud.AIPlatform.V1;
 8 | 
 9 | namespace AutoGen.Gemini;
10 | 
11 | public interface IGeminiClient
12 | {
13 |     Task<GenerateContentResponse> GenerateContentAsync(GenerateContentRequest request, CancellationToken cancellationToken = default);
14 |     IAsyncEnumerable<GenerateContentResponse> GenerateContentStreamAsync(GenerateContentRequest request);
15 | }
16 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.LMStudio/AutoGen.LMStudio.csproj:
--------------------------------------------------------------------------------
 1 | ﻿<Project Sdk="Microsoft.NET.Sdk">
 2 | 
 3 |   <PropertyGroup>
 4 |     <TargetFrameworks>$(PackageTargetFrameworks)</TargetFrameworks>
 5 |     <RootNamespace>AutoGen.LMStudio</RootNamespace>
 6 |   </PropertyGroup>
 7 | 
 8 |   <Import Project="$(RepoRoot)/nuget/nuget-package.props" />
 9 | 
10 |   <PropertyGroup>
11 |     <!-- NuGet Package Settings -->
12 |     <Title>AutoGen.LMStudio</Title>
13 |     <Description>
14 |       Provide support for consuming LMStudio openai-like API service in AutoGen
15 |     </Description>
16 |   </PropertyGroup>
17 | 
18 |   <ItemGroup>
19 |     <ProjectReference Include="..\AutoGen.Core\AutoGen.Core.csproj" />
20 |     <ProjectReference Include="..\AutoGen.OpenAI.V1\AutoGen.OpenAI.V1.csproj" />
21 |   </ItemGroup>
22 | 
23 | </Project>
24 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.LMStudio/GlobalUsing.cs:
--------------------------------------------------------------------------------
1 | // Copyright (c) Microsoft Corporation. All rights reserved.
2 | // GlobalUsing.cs
3 | 
4 | global using AutoGen.Core;
5 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.LMStudio/LMStudioConfig.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // LMStudioConfig.cs
 3 | 
 4 | using System;
 5 | 
 6 | /// <summary>
 7 | /// Add support for consuming openai-like API from LM Studio
 8 | /// </summary>
 9 | public class LMStudioConfig : ILLMConfig
10 | {
11 |     public LMStudioConfig(string host, int port)
12 |     {
13 |         this.Host = host;
14 |         this.Port = port;
15 |         this.Uri = new Uri(
quot;http://{host}:{port}");
16 |     }
17 | 
18 |     public LMStudioConfig(Uri uri)
19 |     {
20 |         this.Uri = uri;
21 |         this.Host = uri.Host;
22 |         this.Port = uri.Port;
23 |     }
24 | 
25 |     public string Host { get; }
26 | 
27 |     public int Port { get; }
28 | 
29 |     public Uri Uri { get; }
30 | }
31 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.Mistral/AutoGen.Mistral.csproj:
--------------------------------------------------------------------------------
 1 | ﻿<Project Sdk="Microsoft.NET.Sdk">
 2 | 
 3 |   <PropertyGroup>
 4 |     <TargetFrameworks>$(PackageTargetFrameworks)</TargetFrameworks>
 5 |     <RootNamespace>AutoGen.Mistral</RootNamespace>
 6 |   </PropertyGroup>
 7 | 
 8 |   <Import Project="$(RepoRoot)/nuget/nuget-package.props" />
 9 | 
10 |   <PropertyGroup>
11 |     <!-- NuGet Package Settings -->
12 |     <Title>AutoGen.Mistral</Title>
13 |     <Description>
14 |       Provide support for consuming Mistral model in AutoGen
15 |     </Description>
16 |   </PropertyGroup>
17 | 
18 |   <ItemGroup>
19 |     <ProjectReference Include="..\AutoGen.Core\AutoGen.Core.csproj" />
20 |   </ItemGroup>
21 | 
22 | 
23 | </Project>
24 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.Mistral/DTOs/ErrorResponse.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // ErrorResponse.cs
 3 | 
 4 | using System.Text.Json.Serialization;
 5 | 
 6 | namespace AutoGen.Mistral;
 7 | 
 8 | public class ErrorResponse
 9 | {
10 |     public ErrorResponse(Error error)
11 |     {
12 |         Error = error;
13 |     }
14 |     /// <summary>
15 |     /// Gets or Sets Error
16 |     /// </summary>
17 |     [JsonPropertyName("error")]
18 |     public Error Error { get; set; }
19 | }
20 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.Mistral/DTOs/FunctionDefinition.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // FunctionDefinition.cs
 3 | 
 4 | using System.Text.Json.Serialization;
 5 | using Json.Schema;
 6 | 
 7 | namespace AutoGen.Mistral;
 8 | 
 9 | public class FunctionDefinition
10 | {
11 |     public FunctionDefinition(string name, string description, JsonSchema? parameters = default)
12 |     {
13 |         Name = name;
14 |         Description = description;
15 |         Parameters = parameters;
16 |     }
17 | 
18 |     [JsonPropertyName("name")]
19 |     public string Name { get; set; }
20 | 
21 |     [JsonPropertyName("description")]
22 |     public string Description { get; set; }
23 | 
24 |     [JsonPropertyName("parameters")]
25 |     public JsonSchema? Parameters { get; set; }
26 | }
27 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.Mistral/DTOs/ResponseFormat.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // ResponseFormat.cs
 3 | 
 4 | using System.Text.Json.Serialization;
 5 | 
 6 | namespace AutoGen.Mistral;
 7 | 
 8 | public class ResponseFormat
 9 | {
10 |     [JsonPropertyName("type")]
11 |     public string ResponseFormatType { get; set; } = "json_object";
12 | }
13 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.Mistral/DTOs/Usage.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // Usage.cs
 3 | 
 4 | using System.Text.Json.Serialization;
 5 | 
 6 | namespace AutoGen.Mistral;
 7 | 
 8 | public class Usage
 9 | {
10 |     [JsonPropertyName("prompt_tokens")]
11 |     public int PromptTokens { get; set; }
12 | 
13 |     /// <summary>
14 |     /// Gets or Sets CompletionTokens
15 |     /// </summary>
16 |     /// <example>93</example>
17 |     [JsonPropertyName("completion_tokens")]
18 |     public int CompletionTokens { get; set; }
19 | 
20 |     /// <summary>
21 |     /// Gets or Sets TotalTokens
22 |     /// </summary>
23 |     /// <example>107</example>
24 |     [JsonPropertyName("total_tokens")]
25 |     public int TotalTokens { get; set; }
26 | }
27 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.Mistral/MistralAIModelID.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // MistralAIModelID.cs
 3 | 
 4 | namespace AutoGen.Mistral;
 5 | 
 6 | public class MistralAIModelID
 7 | {
 8 |     public const string OPEN_MISTRAL_7B = "open-mistral-7b";
 9 |     public const string OPEN_MISTRAL_8X7B = "open-mixtral-8x7b";
10 |     public const string OPEN_MISTRAL_8X22B = "open-mixtral-8x22b";
11 |     public const string MISTRAL_SMALL_LATEST = "mistral-small-latest";
12 |     public const string MISTRAL_MEDIUM_LATEST = "mistral-medium-latest";
13 |     public const string MISTRAL_LARGE_LATEST = "mistral-large-latest";
14 | }
15 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.Ollama/AutoGen.Ollama.csproj:
--------------------------------------------------------------------------------
 1 | ﻿<Project Sdk="Microsoft.NET.Sdk">
 2 | 
 3 |     <PropertyGroup>
 4 |       <TargetFrameworks>$(PackageTargetFrameworks)</TargetFrameworks>
 5 |       <RootNamespace>AutoGen.Ollama</RootNamespace>
 6 |       <GenerateDocumentationFile>True</GenerateDocumentationFile>
 7 |     </PropertyGroup>
 8 | 
 9 |     <Import Project="$(RepoRoot)/nuget/nuget-package.props" />
10 | 
11 |     <PropertyGroup>
12 |       <!-- NuGet Package Settings -->
13 |       <Title>AutoGen.Ollama</Title>
14 |       <Description>
15 |         Provide support for Ollama server in AutoGen
16 |       </Description>
17 |     </PropertyGroup>
18 | 
19 |     <ItemGroup>
20 |       <ProjectReference Include="..\AutoGen.Core\AutoGen.Core.csproj" />
21 |     </ItemGroup>
22 | 
23 | </Project>
24 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.Ollama/DTOs/ChatResponseUpdate.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // ChatResponseUpdate.cs
 3 | 
 4 | using System.Text.Json.Serialization;
 5 | 
 6 | namespace AutoGen.Ollama;
 7 | 
 8 | public class ChatResponseUpdate
 9 | {
10 |     [JsonPropertyName("model")]
11 |     public string Model { get; set; } = string.Empty;
12 | 
13 |     [JsonPropertyName("created_at")]
14 |     public string CreatedAt { get; set; } = string.Empty;
15 | 
16 |     [JsonPropertyName("message")]
17 |     public Message? Message { get; set; }
18 | 
19 |     [JsonPropertyName("done")]
20 |     public bool Done { get; set; }
21 | }
22 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.Ollama/Embeddings/ITextEmbeddingService.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // ITextEmbeddingService.cs
 3 | 
 4 | using System.Threading;
 5 | using System.Threading.Tasks;
 6 | 
 7 | namespace AutoGen.Ollama;
 8 | 
 9 | public interface ITextEmbeddingService
10 | {
11 |     public Task<TextEmbeddingsResponse> GenerateAsync(TextEmbeddingsRequest request, CancellationToken cancellationToken);
12 | }
13 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.Ollama/Embeddings/TextEmbeddingsResponse.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // TextEmbeddingsResponse.cs
 3 | 
 4 | using System.Text.Json.Serialization;
 5 | 
 6 | namespace AutoGen.Ollama;
 7 | 
 8 | public class TextEmbeddingsResponse
 9 | {
10 |     [JsonPropertyName("embedding")]
11 |     public double[]? Embedding { get; set; }
12 | }
13 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.Ollama/OllamaConsts.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // OllamaConsts.cs
 3 | 
 4 | namespace AutoGen.Ollama;
 5 | 
 6 | public class OllamaConsts
 7 | {
 8 |     public const string JsonFormatType = "json";
 9 |     public const string JsonMediaType = "application/json";
10 |     public const string ChatCompletionEndpoint = "/api/chat";
11 |     public const string EmbeddingsEndpoint = "/api/embeddings";
12 | }
13 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.OpenAI.V1/AzureOpenAIConfig.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // AzureOpenAIConfig.cs
 3 | 
 4 | namespace AutoGen.OpenAI.V1;
 5 | 
 6 | public class AzureOpenAIConfig : ILLMConfig
 7 | {
 8 |     public AzureOpenAIConfig(string endpoint, string deploymentName, string apiKey, string? modelId = null)
 9 |     {
10 |         this.Endpoint = endpoint;
11 |         this.DeploymentName = deploymentName;
12 |         this.ApiKey = apiKey;
13 |         this.ModelId = modelId;
14 |     }
15 | 
16 |     public string Endpoint { get; }
17 | 
18 |     public string DeploymentName { get; }
19 | 
20 |     public string ApiKey { get; }
21 | 
22 |     public string? ModelId { get; }
23 | }
24 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.OpenAI.V1/GlobalUsing.cs:
--------------------------------------------------------------------------------
1 | // Copyright (c) Microsoft Corporation. All rights reserved.
2 | // GlobalUsing.cs
3 | 
4 | global using AutoGen.Core;
5 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.OpenAI.V1/OpenAIConfig.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // OpenAIConfig.cs
 3 | 
 4 | namespace AutoGen.OpenAI.V1;
 5 | 
 6 | public class OpenAIConfig : ILLMConfig
 7 | {
 8 |     public OpenAIConfig(string apiKey, string modelId)
 9 |     {
10 |         this.ApiKey = apiKey;
11 |         this.ModelId = modelId;
12 |     }
13 | 
14 |     public string ApiKey { get; }
15 | 
16 |     public string ModelId { get; }
17 | }
18 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.OpenAI/GlobalUsing.cs:
--------------------------------------------------------------------------------
1 | // Copyright (c) Microsoft Corporation. All rights reserved.
2 | // GlobalUsing.cs
3 | 
4 | global using AutoGen.Core;
5 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.SemanticKernel/GlobalUsing.cs:
--------------------------------------------------------------------------------
1 | // Copyright (c) Microsoft Corporation. All rights reserved.
2 | // GlobalUsing.cs
3 | 
4 | global using AutoGen.Core;
5 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.WebAPI/OpenAI/DTO/OpenAIAssistantMessage.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // OpenAIAssistantMessage.cs
 3 | 
 4 | using System.Text.Json.Serialization;
 5 | 
 6 | namespace AutoGen.WebAPI.OpenAI.DTO;
 7 | 
 8 | internal class OpenAIAssistantMessage : OpenAIMessage
 9 | {
10 |     [JsonPropertyName("role")]
11 |     public override string? Role { get; } = "assistant";
12 | 
13 |     [JsonPropertyName("content")]
14 |     public string? Content { get; set; }
15 | 
16 |     [JsonPropertyName("name")]
17 |     public string? Name { get; set; }
18 | 
19 |     [JsonPropertyName("tool_calls")]
20 |     public OpenAIToolCallObject[]? ToolCalls { get; set; }
21 | }
22 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.WebAPI/OpenAI/DTO/OpenAIChatCompletionChoice.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // OpenAIChatCompletionChoice.cs
 3 | 
 4 | using System.Text.Json.Serialization;
 5 | 
 6 | namespace AutoGen.WebAPI.OpenAI.DTO;
 7 | 
 8 | internal class OpenAIChatCompletionChoice
 9 | {
10 |     [JsonPropertyName("finish_reason")]
11 |     public string? FinishReason { get; set; }
12 | 
13 |     [JsonPropertyName("index")]
14 |     public int Index { get; set; }
15 | 
16 |     [JsonPropertyName("message")]
17 |     public OpenAIChatCompletionMessage? Message { get; set; }
18 | 
19 |     [JsonPropertyName("delta")]
20 |     public OpenAIChatCompletionMessage? Delta { get; set; }
21 | }
22 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.WebAPI/OpenAI/DTO/OpenAIChatCompletionMessage.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // OpenAIChatCompletionMessage.cs
 3 | 
 4 | using System.Text.Json.Serialization;
 5 | 
 6 | namespace AutoGen.WebAPI.OpenAI.DTO;
 7 | 
 8 | internal class OpenAIChatCompletionMessage
 9 | {
10 |     [JsonPropertyName("role")]
11 |     public string Role { get; } = "assistant";
12 | 
13 |     [JsonPropertyName("content")]
14 |     public string? Content { get; set; }
15 | }
16 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.WebAPI/OpenAI/DTO/OpenAIChatCompletionUsage.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // OpenAIChatCompletionUsage.cs
 3 | 
 4 | using System.Text.Json.Serialization;
 5 | 
 6 | namespace AutoGen.WebAPI.OpenAI.DTO;
 7 | 
 8 | internal class OpenAIChatCompletionUsage
 9 | {
10 |     [JsonPropertyName("completion_tokens")]
11 |     public int CompletionTokens { get; set; }
12 | 
13 |     [JsonPropertyName("prompt_tokens")]
14 |     public int PromptTokens { get; set; }
15 | 
16 |     [JsonPropertyName("total_tokens")]
17 |     public int TotalTokens { get; set; }
18 | }
19 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.WebAPI/OpenAI/DTO/OpenAIImageUrlObject.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // OpenAIImageUrlObject.cs
 3 | 
 4 | using System.Text.Json.Serialization;
 5 | 
 6 | namespace AutoGen.WebAPI.OpenAI.DTO;
 7 | 
 8 | internal class OpenAIImageUrlObject
 9 | {
10 |     [JsonPropertyName("url")]
11 |     public string? Url { get; set; }
12 | 
13 |     [JsonPropertyName("detail")]
14 |     public string? Detail { get; set; } = "auto";
15 | }
16 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.WebAPI/OpenAI/DTO/OpenAIMessage.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // OpenAIMessage.cs
 3 | 
 4 | using System.Text.Json.Serialization;
 5 | 
 6 | namespace AutoGen.WebAPI.OpenAI.DTO;
 7 | 
 8 | [JsonConverter(typeof(OpenAIMessageConverter))]
 9 | internal abstract class OpenAIMessage
10 | {
11 |     [JsonPropertyName("role")]
12 |     public abstract string? Role { get; }
13 | }
14 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.WebAPI/OpenAI/DTO/OpenAIStreamOptions.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // OpenAIStreamOptions.cs
 3 | 
 4 | using System.Text.Json.Serialization;
 5 | 
 6 | namespace AutoGen.WebAPI.OpenAI.DTO;
 7 | 
 8 | internal class OpenAIStreamOptions
 9 | {
10 |     [JsonPropertyName("include_usage")]
11 |     public bool? IncludeUsage { get; set; }
12 | }
13 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.WebAPI/OpenAI/DTO/OpenAISystemMessage.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // OpenAISystemMessage.cs
 3 | 
 4 | using System.Text.Json.Serialization;
 5 | 
 6 | namespace AutoGen.WebAPI.OpenAI.DTO;
 7 | 
 8 | internal class OpenAISystemMessage : OpenAIMessage
 9 | {
10 |     [JsonPropertyName("role")]
11 |     public override string? Role { get; } = "system";
12 | 
13 |     [JsonPropertyName("content")]
14 |     public string? Content { get; set; }
15 | 
16 |     [JsonPropertyName("name")]
17 |     public string? Name { get; set; }
18 | }
19 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.WebAPI/OpenAI/DTO/OpenAIToolCallObject.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // OpenAIToolCallObject.cs
 3 | 
 4 | using System.Text.Json.Serialization;
 5 | 
 6 | namespace AutoGen.WebAPI.OpenAI.DTO;
 7 | 
 8 | internal class OpenAIToolCallObject
 9 | {
10 |     [JsonPropertyName("name")]
11 |     public string? Name { get; set; }
12 | 
13 |     [JsonPropertyName("arguments")]
14 |     public string? Arguments { get; set; }
15 | }
16 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.WebAPI/OpenAI/DTO/OpenAIToolMessage.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // OpenAIToolMessage.cs
 3 | 
 4 | using System.Text.Json.Serialization;
 5 | 
 6 | namespace AutoGen.WebAPI.OpenAI.DTO;
 7 | 
 8 | internal class OpenAIToolMessage : OpenAIMessage
 9 | {
10 |     [JsonPropertyName("role")]
11 |     public override string? Role { get; } = "tool";
12 | 
13 |     [JsonPropertyName("content")]
14 |     public string? Content { get; set; }
15 | 
16 |     [JsonPropertyName("tool_call_id")]
17 |     public string? ToolCallId { get; set; }
18 | }
19 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.WebAPI/OpenAI/DTO/OpenAIUserImageContent.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // OpenAIUserImageContent.cs
 3 | 
 4 | using System.Text.Json.Serialization;
 5 | 
 6 | namespace AutoGen.WebAPI.OpenAI.DTO;
 7 | 
 8 | internal class OpenAIUserImageContent : OpenAIUserMessageItem
 9 | {
10 |     [JsonPropertyName("type")]
11 |     public override string MessageType { get; } = "image";
12 | 
13 |     [JsonPropertyName("image_url")]
14 |     public string? Url { get; set; }
15 | }
16 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.WebAPI/OpenAI/DTO/OpenAIUserMessage.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // OpenAIUserMessage.cs
 3 | 
 4 | using System.Text.Json.Serialization;
 5 | 
 6 | namespace AutoGen.WebAPI.OpenAI.DTO;
 7 | 
 8 | internal class OpenAIUserMessage : OpenAIMessage
 9 | {
10 |     [JsonPropertyName("role")]
11 |     public override string? Role { get; } = "user";
12 | 
13 |     [JsonPropertyName("content")]
14 |     public string? Content { get; set; }
15 | 
16 |     [JsonPropertyName("name")]
17 |     public string? Name { get; set; }
18 | }
19 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.WebAPI/OpenAI/DTO/OpenAIUserMessageItem.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // OpenAIUserMessageItem.cs
 3 | 
 4 | using System.Text.Json.Serialization;
 5 | 
 6 | namespace AutoGen.WebAPI.OpenAI.DTO;
 7 | 
 8 | internal abstract class OpenAIUserMessageItem
 9 | {
10 |     [JsonPropertyName("type")]
11 |     public abstract string MessageType { get; }
12 | }
13 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.WebAPI/OpenAI/DTO/OpenAIUserMultiModalMessage.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // OpenAIUserMultiModalMessage.cs
 3 | 
 4 | using System.Text.Json.Serialization;
 5 | 
 6 | namespace AutoGen.WebAPI.OpenAI.DTO;
 7 | 
 8 | internal class OpenAIUserMultiModalMessage : OpenAIMessage
 9 | {
10 |     [JsonPropertyName("role")]
11 |     public override string? Role { get; } = "user";
12 | 
13 |     [JsonPropertyName("content")]
14 |     public OpenAIUserMessageItem[]? Content { get; set; }
15 | 
16 |     [JsonPropertyName("name")]
17 |     public string? Name { get; set; }
18 | }
19 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen.WebAPI/OpenAI/DTO/OpenAIUserTextContent.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // OpenAIUserTextContent.cs
 3 | 
 4 | using System.Text.Json.Serialization;
 5 | 
 6 | namespace AutoGen.WebAPI.OpenAI.DTO;
 7 | 
 8 | internal class OpenAIUserTextContent : OpenAIUserMessageItem
 9 | {
10 |     [JsonPropertyName("type")]
11 |     public override string MessageType { get; } = "text";
12 | 
13 |     [JsonPropertyName("text")]
14 |     public string? Content { get; set; }
15 | }
16 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen/ConversableAgentConfig.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // ConversableAgentConfig.cs
 3 | 
 4 | using System.Collections.Generic;
 5 | 
 6 | namespace AutoGen;
 7 | 
 8 | public class ConversableAgentConfig
 9 | {
10 |     public IEnumerable<FunctionContract>? FunctionContracts { get; set; }
11 | 
12 |     public IEnumerable<ILLMConfig>? ConfigList { get; set; }
13 | 
14 |     public float? Temperature { get; set; } = 0.7f;
15 | 
16 |     public int? Timeout { get; set; }
17 | }
18 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen/GlobalUsing.cs:
--------------------------------------------------------------------------------
1 | // Copyright (c) Microsoft Corporation. All rights reserved.
2 | // GlobalUsing.cs
3 | 
4 | global using AutoGen.Core;
5 | 


--------------------------------------------------------------------------------
/dotnet/src/AutoGen/OpenAIConfig.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // OpenAIConfig.cs
 3 | 
 4 | using OpenAI;
 5 | using OpenAI.Chat;
 6 | 
 7 | namespace AutoGen;
 8 | 
 9 | public class OpenAIConfig : ILLMConfig
10 | {
11 |     public OpenAIConfig(string apiKey, string modelId)
12 |     {
13 |         this.ApiKey = apiKey;
14 |         this.ModelId = modelId;
15 |     }
16 | 
17 |     public string ApiKey { get; }
18 | 
19 |     public string ModelId { get; }
20 | 
21 |     internal ChatClient CreateChatClient()
22 |     {
23 |         var client = new OpenAIClient(this.ApiKey);
24 | 
25 |         return client.GetChatClient(this.ModelId);
26 |     }
27 | }
28 | 


--------------------------------------------------------------------------------
/dotnet/src/Microsoft.AutoGen/AgentChat/Abstractions/ITeam.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // ITeam.cs
 3 | 
 4 | using Microsoft.AutoGen.Contracts;
 5 | 
 6 | namespace Microsoft.AutoGen.AgentChat.Abstractions;
 7 | 
 8 | /// <summary>
 9 | /// A team of agents.
10 | /// </summary>
11 | public interface ITeam : ITaskRunner, ISaveState
12 | {
13 |     /// <summary>
14 |     /// Reset the team and all its participants to its initial state.
15 |     /// </summary>
16 |     /// <param name="cancellationToken"></param>
17 |     /// <returns>A <see cref="ValueTask"/> representing the asynchronous operation.</returns>
18 |     ValueTask ResetAsync(CancellationToken cancellationToken = default);
19 | }
20 | 


--------------------------------------------------------------------------------
/dotnet/src/Microsoft.AutoGen/AgentChat/Abstractions/Usage.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // Usage.cs
 3 | 
 4 | namespace Microsoft.AutoGen.AgentChat.Abstractions;
 5 | 
 6 | public struct RequestUsage
 7 | {
 8 |     public int PromptTokens { get; set; }
 9 |     public int CompletionTokens { get; set; }
10 | }
11 | 


--------------------------------------------------------------------------------
/dotnet/src/Microsoft.AutoGen/AgentChat/State/BaseState.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // BaseState.cs
 3 | 
 4 | namespace Microsoft.AutoGen.AgentChat.State;
 5 | 
 6 | [AttributeUsage(AttributeTargets.Class, Inherited = true, AllowMultiple = false)]
 7 | public sealed class StateSerializableAttribute : Attribute
 8 | {
 9 |     public StateSerializableAttribute()
10 |     {
11 |     }
12 | }
13 | 
14 | [StateSerializable]
15 | public abstract class BaseState
16 | {
17 |     public string Type => this.GetType().FullName!;
18 |     public string Version { get; set; } = "1.0.0"; // TODO: More rigorous state versioning?
19 | }
20 | 


--------------------------------------------------------------------------------
/dotnet/src/Microsoft.AutoGen/AgentChat/State/ChatAgentContainerState.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // ChatAgentContainerState.cs
 3 | 
 4 | using Microsoft.AutoGen.AgentChat.Abstractions;
 5 | 
 6 | namespace Microsoft.AutoGen.AgentChat.State;
 7 | 
 8 | public class ChatAgentContainerState : BaseState
 9 | {
10 |     public required SerializedState AgentState { get; set; }
11 |     public List<ChatMessage> MessageBuffer { get; set; } = new();
12 | }
13 | 
14 | public class GroupChatManagerStateBase : BaseState
15 | {
16 |     public List<AgentMessage> MessageThread { get; set; } = new();
17 |     public int CurrentTurn { get; set; }
18 | }
19 | 
20 | public class RoundRobinManagerState : GroupChatManagerStateBase
21 | {
22 |     public int NextSpeakerIndex { get; set; }
23 | }
24 | 


--------------------------------------------------------------------------------
/dotnet/src/Microsoft.AutoGen/AgentChat/State/TeamState.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // TeamState.cs
 3 | 
 4 | namespace Microsoft.AutoGen.AgentChat.State;
 5 | 
 6 | public sealed class TeamState : BaseState
 7 | {
 8 |     public required string TeamId { get; set; }
 9 |     public required SerializedState RuntimeState { get; set; }
10 | }
11 | 


--------------------------------------------------------------------------------
/dotnet/src/Microsoft.AutoGen/AgentHost/.dockerignore:
--------------------------------------------------------------------------------
 1 | **/.classpath
 2 | **/.dockerignore
 3 | **/.env
 4 | **/.git
 5 | **/.gitignore
 6 | **/.project
 7 | **/.settings
 8 | **/.toolstarget
 9 | **/.vs
10 | **/.vscode
11 | **/*.*proj.user
12 | **/*.dbmdl
13 | **/*.jfm
14 | **/azds.yaml
15 | **/bin
16 | **/charts
17 | **/docker-compose*
18 | **/Dockerfile*
19 | **/node_modules
20 | **/npm-debug.log
21 | **/obj
22 | **/secrets.dev.yaml
23 | **/values.dev.yaml
24 | LICENSE
25 | README.md
26 | !**/.gitignore
27 | !.git/HEAD
28 | !.git/config
29 | !.git/packed-refs
30 | !.git/refs/heads/**
31 | /python


--------------------------------------------------------------------------------
/dotnet/src/Microsoft.AutoGen/AgentHost/Program.cs:
--------------------------------------------------------------------------------
1 | // Copyright (c) Microsoft Corporation. All rights reserved.
2 | // Program.cs
3 | using Microsoft.Extensions.Hosting;
4 | 
5 | var app = await Microsoft.AutoGen.RuntimeGateway.Grpc.Host.StartAsync(local: false, useGrpc: true).ConfigureAwait(false);
6 | await app.WaitForShutdownAsync();
7 | 


--------------------------------------------------------------------------------
/dotnet/src/Microsoft.AutoGen/AgentHost/Properties/launchSettings.json:
--------------------------------------------------------------------------------
 1 | {
 2 |   "profiles": {
 3 |     "AgentHost": {
 4 |       "commandName": "Project",
 5 |       "dotnetRunMessages": true,
 6 |       "launchBrowser": true,
 7 |       "applicationUrl": "https://localhost:53071;http://localhost:50673",
 8 |       "environmentVariables": {
 9 |         "ASPNETCORE_ENVIRONMENT": "Development"
10 |       }
11 |     }
12 |   }
13 | }
14 | 


--------------------------------------------------------------------------------
/dotnet/src/Microsoft.AutoGen/AgentHost/appsettings.json:
--------------------------------------------------------------------------------
 1 | {
 2 |   "Logging": {
 3 |     "LogLevel": {
 4 |       "Default": "Warning",
 5 |       "Microsoft.Hosting.Lifetime": "Information",
 6 |       "Microsoft.AspNetCore": "Information",
 7 |       "Microsoft": "Information",
 8 |       "Microsoft.Orleans": "Warning",
 9 |       "Orleans.Runtime": "Error",
10 |       "Grpc": "Information"
11 |     }
12 |   },
13 |   "AllowedHosts": "*",
14 |   "Kestrel": {
15 |     "EndpointDefaults": {
16 |       "Protocols": "Http2"
17 |     }
18 |   }
19 | }
20 | 


--------------------------------------------------------------------------------
/dotnet/src/Microsoft.AutoGen/Contracts/Microsoft.AutoGen.Contracts.csproj:
--------------------------------------------------------------------------------
 1 | <Project Sdk="Microsoft.NET.Sdk">
 2 | 
 3 |   <PropertyGroup>
 4 |     <TargetFramework>net8.0</TargetFramework>
 5 |     <ImplicitUsings>enable</ImplicitUsings>
 6 |     <Nullable>enable</Nullable>
 7 |   </PropertyGroup>
 8 | 
 9 |   <Import Project="$(RepoRoot)/nuget/nuget-package.props" />
10 | </Project>
11 | 


--------------------------------------------------------------------------------
/dotnet/src/Microsoft.AutoGen/Core.Grpc/IProtobufMessageSerializer.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // IProtobufMessageSerializer.cs
 3 | 
 4 | namespace Microsoft.AutoGen.Core.Grpc;
 5 | 
 6 | public interface IProtobufMessageSerializer
 7 | {
 8 |     Google.Protobuf.WellKnownTypes.Any Serialize(object input);
 9 |     object Deserialize(Google.Protobuf.WellKnownTypes.Any input);
10 | }
11 | 


--------------------------------------------------------------------------------
/dotnet/src/Microsoft.AutoGen/Core.Grpc/ITypeNameResolver.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // ITypeNameResolver.cs
 3 | 
 4 | namespace Microsoft.AutoGen.Core.Grpc;
 5 | 
 6 | public interface ITypeNameResolver
 7 | {
 8 |     string ResolveTypeName(Type input);
 9 | }
10 | 


--------------------------------------------------------------------------------
/dotnet/src/Microsoft.AutoGen/Core/Properties/AssemblyInfo.cs:
--------------------------------------------------------------------------------
1 | // Copyright (c) Microsoft Corporation. All rights reserved.
2 | // AssemblyInfo.cs
3 | 
4 | using System.Runtime.CompilerServices;
5 | 
6 | [assembly: InternalsVisibleTo("Microsoft.AutoGen.Core.Tests, PublicKey=0024000004800000940000000602000000240000525341310004000001000100f1d038d0b85ae392ad72011df91e9343b0b5df1bb8080aa21b9424362d696919e0e9ac3a8bca24e283e10f7a569c6f443e1d4e3ebc84377c87ca5caa562e80f9932bf5ea91b7862b538e13b8ba91c7565cf0e8dfeccfea9c805ae3bda044170ecc7fc6f147aeeac422dd96aeb9eb1f5a5882aa650efe2958f2f8107d2038f2ab")]
7 | 


--------------------------------------------------------------------------------
/dotnet/src/Microsoft.AutoGen/Core/ReflectionHelper.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // ReflectionHelper.cs
 3 | 
 4 | namespace Microsoft.AutoGen.Core;
 5 | 
 6 | public sealed class ReflectionHelper
 7 | {
 8 |     public static bool IsSubclassOfGeneric(Type type, Type genericBaseType)
 9 |     {
10 |         while (type != null && type != typeof(object))
11 |         {
12 |             if (genericBaseType == (type.IsGenericType ? type.GetGenericTypeDefinition() : type))
13 |             {
14 |                 return true;
15 |             }
16 |             if (type.BaseType == null)
17 |             {
18 |                 return false;
19 |             }
20 |             type = type.BaseType;
21 |         }
22 | 
23 |         return false;
24 |     }
25 | }
26 | 


--------------------------------------------------------------------------------
/dotnet/src/Microsoft.AutoGen/Core/TypePrefixSubscriptionAttribute.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // TypePrefixSubscriptionAttribute.cs
 3 | 
 4 | using Microsoft.AutoGen.Contracts;
 5 | 
 6 | namespace Microsoft.AutoGen.Core;
 7 | 
 8 | [AttributeUsage(AttributeTargets.All)]
 9 | public class TypePrefixSubscriptionAttribute(string topic) : Attribute, IUnboundSubscriptionDefinition
10 | {
11 |     public string Topic { get; } = topic;
12 | 
13 |     public ISubscriptionDefinition Bind(AgentType agentType)
14 |     {
15 |         return new TypePrefixSubscription(Topic, agentType);
16 |     }
17 | }
18 | 


--------------------------------------------------------------------------------
/dotnet/src/Microsoft.AutoGen/Core/TypeSubscriptionAttribute.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // TypeSubscriptionAttribute.cs
 3 | 
 4 | using Microsoft.AutoGen.Contracts;
 5 | 
 6 | namespace Microsoft.AutoGen.Core;
 7 | 
 8 | [AttributeUsage(AttributeTargets.All)]
 9 | public class TypeSubscriptionAttribute(string topic) : Attribute, IUnboundSubscriptionDefinition
10 | {
11 |     public string Topic { get; } = topic;
12 | 
13 |     public ISubscriptionDefinition Bind(AgentType agentType)
14 |     {
15 |         return new TypeSubscription(Topic, agentType);
16 |     }
17 | }
18 | 


--------------------------------------------------------------------------------
/dotnet/src/Microsoft.AutoGen/Extensions/SemanticKernel/Options/QdrantOptions.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // QdrantOptions.cs
 3 | 
 4 | using System.ComponentModel.DataAnnotations;
 5 | 
 6 | namespace Microsoft.AutoGen.Extensions.SemanticKernel;
 7 | public class QdrantOptions
 8 | {
 9 |     [Required]
10 |     public required string Endpoint { get; set; }
11 |     [Required]
12 |     public required int VectorSize { get; set; }
13 |     public string ApiKey { get; set; } = "";
14 | }
15 | 


--------------------------------------------------------------------------------
/dotnet/src/Microsoft.AutoGen/RuntimeGateway.Grpc/Abstractions/IRegistryGrain.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // IRegistryGrain.cs
 3 | 
 4 | namespace Microsoft.AutoGen.RuntimeGateway.Grpc.Abstractions;
 5 | 
 6 | /// <summary>
 7 | /// Orleans specific interface, needed to mark the key
 8 | /// </summary>
 9 | [Alias("Microsoft.AutoGen.RuntimeGateway.Grpc.Abstractions.IRegistryGrain")]
10 | public interface IRegistryGrain : IGatewayRegistry, IGrainWithIntegerKey
11 | { }
12 | 


--------------------------------------------------------------------------------
/dotnet/src/Microsoft.AutoGen/readme.md:
--------------------------------------------------------------------------------
1 | # Microsoft.AutoGen
2 | 
3 | - [Getting started sample](../../samples/getting-started/)
4 | 


--------------------------------------------------------------------------------
/dotnet/test/.editorconfig:
--------------------------------------------------------------------------------
1 | # Suppressing errors for Test projects under test folder
2 | [*.cs]
3 | dotnet_diagnostic.CA2007.severity = none # Do not directly await a Task
4 | dotnet_diagnostic.VSTHRD111.severity = none # Use .ConfigureAwait(bool) is hidden by default, set to none to prevent IDE from changing on autosave
5 | dotnet_diagnostic.CS1591.severity = none # Missing XML comment for publicly visible type or member
6 | dotnet_diagnostic.CS1998.severity = none # Async method lacks 'await' operators and will run synchronously
7 | dotnet_diagnostic.IDE1006.severity = warning # Naming rule violations


--------------------------------------------------------------------------------
/dotnet/test/AutoGen.Anthropic.Tests/images/.gitattributes:
--------------------------------------------------------------------------------
1 | square.png filter=lfs diff=lfs merge=lfs -text
2 | 


--------------------------------------------------------------------------------
/dotnet/test/AutoGen.Anthropic.Tests/images/square.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:8341030e5b93aab2c55dcd40ffa26ced8e42cc15736a8348176ffd155ad2d937
3 | size 8167
4 | 


--------------------------------------------------------------------------------
/dotnet/test/AutoGen.AotCompatibility.Tests/Program.cs:
--------------------------------------------------------------------------------
1 | // Copyright (c) Microsoft Corporation. All rights reserved.
2 | // Program.cs
3 | 
4 | Console.WriteLine("Hello, World!");
5 | 


--------------------------------------------------------------------------------
/dotnet/test/AutoGen.Gemini.Tests/ApprovalTests/FunctionContractExtensionTests.ItGenerateGetWeatherToolTest.approved.txt:
--------------------------------------------------------------------------------
 1 | ﻿{
 2 |   "name": "GetWeatherAsync",
 3 |   "description": "Get weather for a city.",
 4 |   "parameters": {
 5 |     "type": "OBJECT",
 6 |     "properties": {
 7 |       "city": {
 8 |         "type": "STRING",
 9 |         "description": "city",
10 |         "title": "city"
11 |       }
12 |     },
13 |     "required": [
14 |       "city"
15 |     ]
16 |   }
17 | }


--------------------------------------------------------------------------------
/dotnet/test/AutoGen.Ollama.Tests/images/image.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:300b7c9d6ba0c23a3e52fbd2e268141ddcca0434a9fb9dcf7e58e7e903d36dcf
3 | size 2126185
4 | 


--------------------------------------------------------------------------------
/dotnet/test/AutoGen.Ollama.Tests/images/square.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:8323d0b8eceb752e14c29543b2e28bb2fc648ed9719095c31b7708867a4dc918
3 | size 491
4 | 


--------------------------------------------------------------------------------
/dotnet/test/AutoGen.OpenAI.Tests/GlobalUsing.cs:
--------------------------------------------------------------------------------
1 | // Copyright (c) Microsoft Corporation. All rights reserved.
2 | // GlobalUsing.cs
3 | 
4 | global using AutoGen.Core;
5 | 


--------------------------------------------------------------------------------
/dotnet/test/AutoGen.OpenAI.V1.Tests/GlobalUsing.cs:
--------------------------------------------------------------------------------
1 | // Copyright (c) Microsoft Corporation. All rights reserved.
2 | // GlobalUsing.cs
3 | 
4 | global using AutoGen.Core;
5 | 


--------------------------------------------------------------------------------
/dotnet/test/AutoGen.SemanticKernel.Tests/ApprovalTests/KernelFunctionExtensionTests.ItCreateFunctionContractsFromPrompt.approved.txt:
--------------------------------------------------------------------------------
1 | ﻿[
2 |   {
3 |     "Name": "sayHello",
4 |     "Description": "Generic function, unknown purpose",
5 |     "Parameters": [],
6 |     "ReturnDescription": ""
7 |   }
8 | ]


--------------------------------------------------------------------------------
/dotnet/test/AutoGen.SourceGenerator.Tests/ApprovalTests/FunctionExample.Add_Test.approved.txt:
--------------------------------------------------------------------------------
 1 | {
 2 |   "name": "Add",
 3 |   "description": "Add function",
 4 |   "parameters": {
 5 |     "type": "object",
 6 |     "properties": {
 7 |       "a": {
 8 |         "type": "integer",
 9 |         "description": "a"
10 |       },
11 |       "b": {
12 |         "type": "integer",
13 |         "description": "b"
14 |       }
15 |     },
16 |     "required": [
17 |       "a",
18 |       "b"
19 |     ]
20 |   }
21 | }


--------------------------------------------------------------------------------
/dotnet/test/AutoGen.SourceGenerator.Tests/ApprovalTests/FunctionExample.DictionaryToString_Test.approved.txt:
--------------------------------------------------------------------------------
 1 | {
 2 |   "name": "DictionaryToStringAsync",
 3 |   "description": "DictionaryToString function",
 4 |   "parameters": {
 5 |     "type": "object",
 6 |     "properties": {
 7 |       "xargs": {
 8 |         "type": "object",
 9 |         "additionalProperties": {
10 |           "type": "string"
11 |         },
12 |         "description": "an object of key-value pairs. key is string, value is string"
13 |       }
14 |     },
15 |     "required": [
16 |       "xargs"
17 |     ]
18 |   }
19 | }


--------------------------------------------------------------------------------
/dotnet/test/AutoGen.SourceGenerator.Tests/ApprovalTests/FunctionExample.Query_Test.approved.txt:
--------------------------------------------------------------------------------
 1 | {
 2 |   "name": "Query",
 3 |   "description": "query function",
 4 |   "parameters": {
 5 |     "type": "object",
 6 |     "properties": {
 7 |       "query": {
 8 |         "type": "string",
 9 |         "description": "query, required"
10 |       },
11 |       "k": {
12 |         "type": "integer",
13 |         "description": "top k, optional, default value is 3"
14 |       },
15 |       "thresold": {
16 |         "type": "number",
17 |         "description": "thresold, optional, default value is 0.5"
18 |       }
19 |     },
20 |     "required": [
21 |       "query"
22 |     ]
23 |   }
24 | }


--------------------------------------------------------------------------------
/dotnet/test/AutoGen.SourceGenerator.Tests/ApprovalTests/FunctionExample.Sum_Test.approved.txt:
--------------------------------------------------------------------------------
 1 | {
 2 |   "name": "Sum",
 3 |   "description": "Sum function",
 4 |   "parameters": {
 5 |     "type": "object",
 6 |     "properties": {
 7 |       "args": {
 8 |         "type": "array",
 9 |         "items": {
10 |           "type": "number"
11 |         },
12 |         "description": "an array of double values"
13 |       }
14 |     },
15 |     "required": [
16 |       "args"
17 |     ]
18 |   }
19 | }


--------------------------------------------------------------------------------
/dotnet/test/AutoGen.SourceGenerator.Tests/AutoGen.SourceGenerator.Tests.csproj:
--------------------------------------------------------------------------------
 1 | <Project Sdk="Microsoft.NET.Sdk">
 2 | 
 3 |   <PropertyGroup>
 4 |     <TargetFrameworks>$(TestTargetFrameworks)</TargetFrameworks>
 5 |     <ImplicitUsings>enable</ImplicitUsings>
 6 |     <IsPackable>false</IsPackable>
 7 |     <IsTestProject>True</IsTestProject>
 8 | 	  <GenerateDocumentationFile>True</GenerateDocumentationFile>
 9 |     <NoWarn>$(NoWarn);CA1829;CA1826</NoWarn>
10 |   </PropertyGroup>
11 | 
12 |   <ItemGroup>
13 |     <ProjectReference Include="..\..\src\AutoGen.SourceGenerator\AutoGen.SourceGenerator.csproj" OutputItemType="Analyzer" ReferenceOutputAssembly="true" />
14 |     <ProjectReference Include="..\..\src\AutoGen\AutoGen.csproj" />
15 |   </ItemGroup>
16 | 	
17 | </Project>


--------------------------------------------------------------------------------
/dotnet/test/AutoGen.SourceGenerator.Tests/FilescopeNamespaceFunctionExample.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // FilescopeNamespaceFunctionExample.cs
 3 | 
 4 | using AutoGen.Core;
 5 | 
 6 | namespace AutoGen.SourceGenerator.Tests;
 7 | public partial class FilescopeNamespaceFunctionExample
 8 | {
 9 |     [Function]
10 |     public Task<string> Add(int a, int b)
11 |     {
12 |         return Task.FromResult(
quot;{a + b}");
13 |     }
14 | }
15 | 


--------------------------------------------------------------------------------
/dotnet/test/AutoGen.SourceGenerator.Tests/TopLevelStatementFunctionExample.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // TopLevelStatementFunctionExample.cs
 3 | 
 4 | using AutoGen.Core;
 5 | 
 6 | public partial class TopLevelStatementFunctionExample
 7 | {
 8 |     [Function]
 9 |     public Task<string> Add(int a, int b)
10 |     {
11 |         return Task.FromResult(
quot;{a + b}");
12 |     }
13 | }
14 | 


--------------------------------------------------------------------------------
/dotnet/test/AutoGen.Test.Share/Attribute/OpenAIFact.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // OpenAIFact.cs
 3 | 
 4 | namespace AutoGen.Tests;
 5 | 
 6 | /// <summary>
 7 | /// A fact for tests requiring OPENAI_API_KEY env.
 8 | /// </summary>
 9 | public sealed class ApiKeyFactAttribute : EnvironmentSpecificFactAttribute
10 | {
11 |     private readonly string[] _envVariableNames;
12 |     public ApiKeyFactAttribute(params string[] envVariableNames) : base(
quot;{envVariableNames} is not found in env")
13 |     {
14 |         _envVariableNames = envVariableNames;
15 |     }
16 | 
17 |     /// <inheritdoc />
18 |     protected override bool IsEnvironmentSupported()
19 |     {
20 |         return _envVariableNames.All(Environment.GetEnvironmentVariables().Contains);
21 |     }
22 | }
23 | 


--------------------------------------------------------------------------------
/dotnet/test/AutoGen.Test.Share/AutoGen.Tests.Share.csproj:
--------------------------------------------------------------------------------
 1 | ﻿<Project Sdk="Microsoft.NET.Sdk">
 2 | 
 3 |   <PropertyGroup>
 4 |     <TargetFrameworks>$(TestTargetFrameworks)</TargetFrameworks>
 5 |     <ImplicitUsings>enable</ImplicitUsings>
 6 |     <IsPackable>false</IsPackable>
 7 |     <IsTestProject>True</IsTestProject>
 8 |     <Nullable>enable</Nullable>
 9 |   </PropertyGroup>
10 | 
11 |   <ItemGroup>
12 |     <ProjectReference Include="..\..\src\AutoGen.Core\AutoGen.Core.csproj" />
13 |   </ItemGroup>
14 | 
15 | </Project>
16 | 


--------------------------------------------------------------------------------
/dotnet/test/AutoGen.Tests/ApprovalTests/square.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:8323d0b8eceb752e14c29543b2e28bb2fc648ed9719095c31b7708867a4dc918
3 | size 491
4 | 


--------------------------------------------------------------------------------
/dotnet/test/AutoGen.Tests/GlobalUsing.cs:
--------------------------------------------------------------------------------
1 | // Copyright (c) Microsoft Corporation. All rights reserved.
2 | // GlobalUsing.cs
3 | 
4 | global using AutoGen.Core;
5 | 


--------------------------------------------------------------------------------
/dotnet/test/AutoGen.Tests/GroupChat/GraphTests.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // GraphTests.cs
 3 | 
 4 | using Xunit;
 5 | 
 6 | namespace AutoGen.Tests;
 7 | 
 8 | [Trait("Category", "UnitV1")]
 9 | public class GraphTests
10 | {
11 |     [Fact]
12 |     public void GraphTest()
13 |     {
14 |         var graph1 = new Graph();
15 |         Assert.NotNull(graph1);
16 | 
17 |         var graph2 = new Graph(null);
18 |         Assert.NotNull(graph2);
19 |     }
20 | }
21 | 


--------------------------------------------------------------------------------
/dotnet/test/Microsoft.AutoGen.Core.Grpc.Tests/Properties/launchSettings.json:
--------------------------------------------------------------------------------
 1 | {
 2 |   "profiles": {
 3 |     "AgentHost": {
 4 |       "commandName": "Project",
 5 |       "dotnetRunMessages": true,
 6 |       "launchBrowser": true,
 7 |       "applicationUrl": "https://localhost:50670;http://localhost:50673",
 8 |       "environmentVariables": {
 9 |         "ASPNETCORE_ENVIRONMENT": "Development"
10 |       }
11 |     }
12 |   }
13 | }
14 | 


--------------------------------------------------------------------------------
/dotnet/test/Microsoft.AutoGen.Core.Grpc.Tests/TestBase.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // TestBase.cs
 3 | 
 4 | namespace Microsoft.AutoGen.Core.Grpc.Tests;
 5 | 
 6 | public class TestBase
 7 | {
 8 |     public TestBase()
 9 |     {
10 |         try
11 |         {
12 |             // For some reason the first call to StartAsync() throws when these tests
13 |             // run in parallel, even though the port does not actually collide between
14 |             // different instances of GrpcAgentRuntimeFixture. This is a workaround.
15 |             _ = new GrpcAgentRuntimeFixture().StartAsync().Result;
16 |         }
17 |         catch (Exception e)
18 |         {
19 |             Console.WriteLine(e);
20 |         }
21 |     }
22 | }
23 | 


--------------------------------------------------------------------------------
/dotnet/test/Microsoft.AutoGen.Core.Grpc.Tests/appsettings.json:
--------------------------------------------------------------------------------
 1 | {
 2 |   "Logging": {
 3 |     "LogLevel": {
 4 |       "Default": "Warning",
 5 |       "Microsoft": "Warning",
 6 |       "Microsoft.Orleans": "Warning",
 7 |       "Orleans.Runtime": "Debug",
 8 |       "Grpc": "Information"
 9 |     }
10 |   },
11 |   "AllowedHosts": "*",
12 |   "Kestrel": {
13 |     "EndpointDefaults": {
14 |       "Protocols": "Http2"
15 |     }
16 |   }
17 | }
18 | 


--------------------------------------------------------------------------------
/dotnet/test/Microsoft.AutoGen.Core.Grpc.Tests/messages.proto:
--------------------------------------------------------------------------------
 1 | syntax = "proto3";
 2 | 
 3 | option csharp_namespace = "Microsoft.AutoGen.Core.Grpc.Tests.Protobuf";
 4 | 
 5 | message TextMessage {
 6 |     string content = 1;
 7 |     string source = 2;
 8 | }
 9 | 
10 | message RpcTextMessage {
11 |     string content = 1;
12 |     string source = 2;
13 | }


--------------------------------------------------------------------------------
/dotnet/test/Microsoft.AutoGen.Core.Tests/AgentMetaDataTests.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // AgentMetaDataTests.cs
 3 | using FluentAssertions;
 4 | using Microsoft.AutoGen.Contracts;
 5 | using Xunit;
 6 | 
 7 | namespace Microsoft.AutoGen.Core.Tests;
 8 | 
 9 | [Trait("Category", "UnitV2")]
10 | public class AgentMetadataTests()
11 | {
12 |     [Fact]
13 |     public void AgentMetadataShouldInitializeCorrectlyTest()
14 |     {
15 |         var metadata = new AgentMetadata("TestType", "TestKey", "TestDescription");
16 | 
17 |         metadata.Type.Should().Be("TestType");
18 |         metadata.Key.Should().Be("TestKey");
19 |         metadata.Description.Should().Be("TestDescription");
20 |     }
21 | }
22 | 


--------------------------------------------------------------------------------
/dotnet/test/Microsoft.AutoGen.Core.Tests/InProcessRuntimeExtensions.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // InProcessRuntimeExtensions.cs
 3 | namespace Microsoft.AutoGen.Core.Tests;
 4 | 
 5 | public static class InProcessRuntimeExtensions
 6 | {
 7 |     public static async ValueTask RunUntilIdleAndRestartAsync(this InProcessRuntime this_)
 8 |     {
 9 |         await this_.RunUntilIdleAsync();
10 |         await this_.StartAsync();
11 |     }
12 | }
13 | 


--------------------------------------------------------------------------------
/dotnet/test/Microsoft.AutoGen.Core.Tests/TestMessages.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // TestMessages.cs
 3 | 
 4 | namespace Microsoft.AutoGen.Core.Tests;
 5 | 
 6 | public class TextMessage
 7 | {
 8 |     public string Source { get; set; } = "";
 9 |     public string Content { get; set; } = "";
10 | }
11 | 
12 | public class RpcTextMessage
13 | {
14 |     public string Source { get; set; } = "";
15 |     public string Content { get; set; } = "";
16 | }
17 | 
18 | public sealed class BasicMessage
19 | {
20 |     public string Content { get; set; } = string.Empty;
21 | }
22 | 
23 | 


--------------------------------------------------------------------------------
/dotnet/test/Microsoft.AutoGen.Integration.Tests.AppHosts/HelloAgentTests/Properties/launchSettings.json:
--------------------------------------------------------------------------------
 1 | {
 2 |   "profiles": {
 3 |     "HelloAgent": {
 4 |       "commandName": "Project",
 5 |       "launchBrowser": true,
 6 |       "environmentVariables": {
 7 |         "ASPNETCORE_ENVIRONMENT": "Development"
 8 |       },
 9 |       "applicationUrl": "https://localhost:53113;http://localhost:53114"
10 |     }
11 |   }
12 | }
13 | 


--------------------------------------------------------------------------------
/dotnet/test/Microsoft.AutoGen.Integration.Tests.AppHosts/HelloAgentTests/appsettings.json:
--------------------------------------------------------------------------------
 1 | {
 2 |   "Logging": {
 3 |     "LogLevel": {
 4 |       "Default": "Warning",
 5 |       "Microsoft.Hosting.Lifetime": "Information",
 6 |       "Microsoft.AspNetCore": "Information",
 7 |       "Microsoft": "Information",
 8 |       "Microsoft.Orleans": "Warning",
 9 |       "Orleans.Runtime": "Error",
10 |       "Grpc": "Information"
11 |     }
12 |   },
13 |   "AllowedHosts": "*",
14 |   "Kestrel": {
15 |     "EndpointDefaults": {
16 |       "Protocols": "Http2"
17 |     }
18 |   }
19 | }


--------------------------------------------------------------------------------
/dotnet/test/Microsoft.AutoGen.Integration.Tests.AppHosts/InMemoryTests.AppHost/InMemoryTests.AppHost.csproj:
--------------------------------------------------------------------------------
 1 | <Project Sdk="Microsoft.NET.Sdk">
 2 | 
 3 |   <Sdk Name="Aspire.AppHost.Sdk" Version="9.0.0" />
 4 | 
 5 |   <PropertyGroup>
 6 |     <OutputType>Exe</OutputType>
 7 |         <TargetFramework>net8.0</TargetFramework>
 8 |     <ImplicitUsings>enable</ImplicitUsings>
 9 |     <Nullable>enable</Nullable>
10 |     <IsAspireHost>true</IsAspireHost>
11 |   </PropertyGroup>
12 | 
13 |   <ItemGroup>
14 |     <PackageReference Include="Aspire.Hosting.AppHost" />
15 |     <PackageReference Include="Aspire.Hosting" />
16 |   </ItemGroup>
17 | 
18 |   <ItemGroup>
19 |     <ProjectReference Include="../HelloAgentTests/HelloAgentTests.csproj" />
20 |   </ItemGroup>
21 | </Project>
22 | 


--------------------------------------------------------------------------------
/dotnet/test/Microsoft.AutoGen.Integration.Tests.AppHosts/InMemoryTests.AppHost/Program.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // Program.cs
 3 | 
 4 | using Microsoft.Extensions.Hosting;
 5 | 
 6 | var appHost = DistributedApplication.CreateBuilder();
 7 | appHost.AddProject<Projects.HelloAgentTests>("HelloAgentsDotNetInMemoryRuntime");
 8 | var app = appHost.Build();
 9 | await app.StartAsync();
10 | await app.WaitForShutdownAsync();
11 | 


--------------------------------------------------------------------------------
/dotnet/test/Microsoft.AutoGen.Integration.Tests.AppHosts/core_xlang_hello_python_agent/protos/__init__.py:
--------------------------------------------------------------------------------
1 | """
2 | The :mod:`autogen_core.worker.protos` module provides Google Protobuf classes for agent-worker communication
3 | """
4 | 
5 | import os
6 | import sys
7 | 
8 | sys.path.insert(0, os.path.abspath(os.path.dirname(__file__)))
9 | 


--------------------------------------------------------------------------------
/dotnet/test/Microsoft.AutoGen.Integration.Tests.AppHosts/core_xlang_hello_python_agent/protos/agent_events_pb2_grpc.pyi:
--------------------------------------------------------------------------------
 1 | """
 2 | @generated by mypy-protobuf.  Do not edit manually!
 3 | isort:skip_file
 4 | """
 5 | 
 6 | import abc
 7 | import collections.abc
 8 | import grpc
 9 | import grpc.aio
10 | import typing
11 | 
12 | _T = typing.TypeVar("_T")
13 | 
14 | class _MaybeAsyncIterator(collections.abc.AsyncIterator[_T], collections.abc.Iterator[_T], metaclass=abc.ABCMeta): ...
15 | 
16 | class _ServicerContext(grpc.ServicerContext, grpc.aio.ServicerContext):  # type: ignore[misc, type-arg]
17 |     ...
18 | 


--------------------------------------------------------------------------------
/dotnet/test/Microsoft.AutoGen.RuntimeGateway.Grpc.Tests/Helpers/Orleans/ClusterCollection.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // ClusterCollection.cs
 3 | 
 4 | namespace Microsoft.AutoGen.RuntimeGateway.Grpc.Tests.Helpers.Orleans;
 5 | 
 6 | [CollectionDefinition(Name)]
 7 | public sealed class ClusterCollection : ICollectionFixture<ClusterFixture>
 8 | {
 9 |     public const string Name = nameof(ClusterCollection);
10 | }
11 | 


--------------------------------------------------------------------------------
/dotnet/test/Microsoft.AutoGen.RuntimeGateway.Grpc.Tests/Helpers/Orleans/ClusterFixture.cs:
--------------------------------------------------------------------------------
 1 | // Copyright (c) Microsoft Corporation. All rights reserved.
 2 | // ClusterFixture.cs
 3 | 
 4 | using Orleans.TestingHost;
 5 | 
 6 | namespace Microsoft.AutoGen.RuntimeGateway.Grpc.Tests.Helpers.Orleans;
 7 | 
 8 | public sealed class ClusterFixture : IDisposable
 9 | {
10 |     public ClusterFixture()
11 |     {
12 |         var builder = new TestClusterBuilder();
13 |         builder.AddSiloBuilderConfigurator<SiloBuilderConfigurator>();
14 |         Cluster = builder.Build();
15 |         Cluster.Deploy();
16 |     }
17 |     public TestCluster Cluster { get; }
18 | 
19 |     void IDisposable.Dispose() => Cluster.StopAllSilos();
20 | }
21 | 


--------------------------------------------------------------------------------
/dotnet/website/.gitignore:
--------------------------------------------------------------------------------
 1 | ###############
 2 | #    folder   #
 3 | ###############
 4 | /**/DROP/
 5 | /**/TEMP/
 6 | /**/packages/
 7 | /**/bin/
 8 | /**/obj/
 9 | 
10 | # build artifacts for web
11 | _site/
12 | api/
13 | 


--------------------------------------------------------------------------------
/dotnet/website/README.md:
--------------------------------------------------------------------------------
 1 | ## How to build and run the website
 2 | 
 3 | ### Prerequisites
 4 | - dotnet 7.0 or later
 5 | 
 6 | ### Build
 7 | Firstly, go to autogen/dotnet folder and run the following command to build the website:
 8 | ```bash
 9 | dotnet tool restore
10 | dotnet tool run docfx website/docfx.json --serve
11 | ```
12 | 
13 | After the command is executed, you can open your browser and navigate to `http://localhost:8080` to view the website.


--------------------------------------------------------------------------------
/dotnet/website/articles/AutoGen.Gemini/Overview.md:
--------------------------------------------------------------------------------
 1 | # AutoGen.Gemini Overview
 2 | 
 3 | AutoGen.Gemini is a package that provides seamless integration with Google Gemini. It provides the following agent:
 4 | 
 5 | - @AutoGen.Gemini.GeminiChatAgent: The agent that connects to Google Gemini or Vertex AI Gemini. It supports chat, multi-modal chat, and function call.
 6 | 
 7 | AutoGen.Gemini also provides the following middleware:
 8 | - @AutoGen.Gemini.GeminiMessageConnector: The middleware that converts the Gemini message to AutoGen built-in message type.
 9 | 
10 | ## Examples
11 | 
12 | You can find more examples under the [gemini sample project](https://github.com/microsoft/autogen/tree/main/dotnet/samples/AutoGen.Gemini.Sample)


--------------------------------------------------------------------------------
/dotnet/website/articles/Create-an-agent.md:
--------------------------------------------------------------------------------
 1 | ## AssistantAgent
 2 | 
 3 | [`AssistantAgent`](../api/AutoGen.AssistantAgent.yml) is a built-in agent in `AutoGen` that acts as an AI assistant. It uses LLM to generate response to user input. It also supports function call if the underlying LLM model supports it (e.g. `gpt-3.5-turbo-0613`).
 4 | 
 5 | ## Create an `AssistantAgent` using OpenAI model.
 6 | 
 7 | [!code-csharp[](../../samples/AgentChat/Autogen.Basic.Sample/CodeSnippet/CreateAnAgent.cs?name=code_snippet_1)]
 8 | 
 9 | ## Create an `AssistantAgent` using Azure OpenAI model.
10 | 
11 | [!code-csharp[](../../samples/AgentChat/Autogen.Basic.Sample/CodeSnippet/CreateAnAgent.cs?name=code_snippet_2)]
12 | 


--------------------------------------------------------------------------------
/dotnet/website/articles/Create-your-own-agent.md:
--------------------------------------------------------------------------------
1 | ## Coming soon


--------------------------------------------------------------------------------
/dotnet/website/articles/Create-your-own-middleware.md:
--------------------------------------------------------------------------------
1 | ## Coming soon


--------------------------------------------------------------------------------
/dotnet/website/articles/Function-call-middleware.md:
--------------------------------------------------------------------------------
1 | # Coming soon


--------------------------------------------------------------------------------
/dotnet/website/articles/OpenAIChatAgent-simple-chat.md:
--------------------------------------------------------------------------------
 1 | The following example shows how to create an @AutoGen.OpenAI.OpenAIChatAgent and chat with it.
 2 | 
 3 | Firsly, import the required namespaces:
 4 | [!code-csharp[](../../samples/AgentChat/Autogen.Basic.Sample/CodeSnippet/OpenAICodeSnippet.cs?name=using_statement)]
 5 | 
 6 | Then, create an @AutoGen.OpenAI.OpenAIChatAgent and chat with it:
 7 | [!code-csharp[](../../samples/AgentChat/Autogen.Basic.Sample/CodeSnippet/OpenAICodeSnippet.cs?name=create_openai_chat_agent)]
 8 | 
 9 | @AutoGen.OpenAI.OpenAIChatAgent also supports streaming chat via @AutoGen.Core.IAgent.GenerateStreamingReplyAsync*.
10 | 
11 | [!code-csharp[](../../samples/AgentChat/Autogen.Basic.Sample/CodeSnippet/OpenAICodeSnippet.cs?name=create_openai_chat_agent_streaming)]


--------------------------------------------------------------------------------
/dotnet/website/filterConfig.yml:
--------------------------------------------------------------------------------
1 | apiRules:
2 | - exclude:
3 |     uidRegex: ^AutoGen.SourceGenerator


--------------------------------------------------------------------------------
/dotnet/website/images/ag.ico:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/dotnet/website/images/ag.ico


--------------------------------------------------------------------------------
/dotnet/website/images/articles/ConnectTo3PartyOpenAI/output.gif:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/dotnet/website/images/articles/ConnectTo3PartyOpenAI/output.gif


--------------------------------------------------------------------------------
/dotnet/website/images/articles/CreateAgentWithTools/single-turn-tool-call-with-auto-invoke.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:f0d8e2ab194e31dc70e39ba081a755c8e792d291bef4dc8b4c5cc372bed9ec50
3 | size 215389
4 | 


--------------------------------------------------------------------------------
/dotnet/website/images/articles/CreateAgentWithTools/single-turn-tool-call-without-auto-invoke.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:5f2e632fb24641eb2fac7fff995c9b3213023c45c3238531eec5a340072865f6
3 | size 202768
4 | 


--------------------------------------------------------------------------------
/dotnet/website/images/articles/CreateUserProxyAgent/image-1.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:91813a034edc3918a27758296d77150d1c8d650911847bdc6a42cca79307714a
3 | size 9009
4 | 


--------------------------------------------------------------------------------
/dotnet/website/images/articles/DynamicGroupChat/dynamicChat.gif:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:5cba3069e9669a1b8013f0b2fa4d191c1d7b0b7919b1664f1f8ec98a90c7a2b2
3 | size 411517
4 | 


--------------------------------------------------------------------------------
/dotnet/website/images/articles/PrintMessageMiddleware/printMessage.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:7ec3bc40d4e3c1228d5799e448a34521998e7abb700bc978afc790389805ecb4
3 | size 86924
4 | 


--------------------------------------------------------------------------------
/dotnet/website/images/articles/PrintMessageMiddleware/streamingoutput.gif:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:95feb667fe74177506435ca52fcf183fb187a3a407fac0b3b220bd9e8da721c7
3 | size 547023
4 | 


--------------------------------------------------------------------------------
/dotnet/website/images/articles/SequentialGroupChat/SearcherSummarizer.gif:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:c6d8a5a534efaf49ecc796ad3ca8e62fb7a236b55d894bda7a0c258564195b5d
3 | size 620269
4 | 


--------------------------------------------------------------------------------
/dotnet/website/images/articles/UseAutoGenAsModelinAGStudio/FinalStepsA.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:491f8f538c55ce8768179cabfd3789c71c4a07b7d809f85deba9b8f4b759c00e
3 | size 42329
4 | 


--------------------------------------------------------------------------------
/dotnet/website/images/articles/UseAutoGenAsModelinAGStudio/FinalStepsB.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:e319fad11682c46c3dc511e2fc63e033f3f99efb06d4530e7f72d1f4af23848f
3 | size 31528
4 | 


--------------------------------------------------------------------------------
/dotnet/website/images/articles/UseAutoGenAsModelinAGStudio/FinalStepsC.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:a8024b5336615e8c2c3497df7a5890a331bd5bdc7b15dd06abd7ec528ffe0932
3 | size 70169
4 | 


--------------------------------------------------------------------------------
/dotnet/website/images/articles/UseAutoGenAsModelinAGStudio/Step5.2OpenAIModel.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:911f2f7c1ab4f9403386298d9769243c0aa8cc22c6f119342cc107a654d1463a
3 | size 44041
4 | 


--------------------------------------------------------------------------------
/dotnet/website/images/articles/UseAutoGenAsModelinAGStudio/Step5.3ModelNameAndURL.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:ec10a48ed3f0a6d8448e0ce425658f3857c2cf89e2badef8a8d3a8c3744fc3bf
3 | size 51944
4 | 


--------------------------------------------------------------------------------
/dotnet/website/images/articles/UseAutoGenAsModelinAGStudio/Step6.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:f016faea51f64af3970fde41ac95249c4e0423b02573f058c36dc1e6ba15562d
3 | size 50669
4 | 


--------------------------------------------------------------------------------
/dotnet/website/images/articles/UseAutoGenAsModelinAGStudio/Step6b.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:4a23cbbf5d3d24eaf1da9370e0914f186815f2ecbf46131d2fd6eb5ff3264d96
3 | size 22569
4 | 


--------------------------------------------------------------------------------
/dotnet/website/images/articles/UseAutoGenAsModelinAGStudio/Terminal.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:97328776c25fd0a61c76065db379406d8d3c96bd8773490c34c168cd7c69a855
3 | size 58527
4 | 


--------------------------------------------------------------------------------
/dotnet/website/images/articles/UseAutoGenAsModelinAGStudio/TheModelTab.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:1d7f4f3a772278e6de320a3601a76f8a9862cab4a9c0da03fad3058b86fcfaf7
3 | size 45260
4 | 


--------------------------------------------------------------------------------
/dotnet/website/index.md:
--------------------------------------------------------------------------------
1 | [!INCLUDE [](./articles/getting-start.md)]


--------------------------------------------------------------------------------
/dotnet/website/release_note/0.2.1.md:
--------------------------------------------------------------------------------
1 | ﻿# Release Notes for AutoGen.Net v0.2.1 🚀
2 | 
3 | ## New Features 🌟
4 | - **Support for OpenAi o1-preview** : Added support for OpenAI o1-preview model ([#3522](https://github.com/microsoft/autogen/issues/3522))
5 | 
6 | ## Example 📚
7 | - **OpenAI o1-preview**: [Connect_To_OpenAI_o1_preview](https://github.com/microsoft/autogen/blob/main/dotnet/samples/AutoGen.OpenAI.Sample/Connect_To_OpenAI_o1_preview.cs)


--------------------------------------------------------------------------------
/dotnet/website/release_note/0.2.2.md:
--------------------------------------------------------------------------------
1 | ﻿# Release Notes for AutoGen.Net v0.2.2 🚀
2 | 
3 | ## Improvements 🌟
4 | - **Update OpenAI and Semantick Kernel to the latest version** : Updated OpenAI and Semantick Kernel to the latest version ([#3792](https://github.com/microsoft/autogen/pull/3792)


--------------------------------------------------------------------------------
/dotnet/website/release_note/toc.yml:
--------------------------------------------------------------------------------
 1 | - name: 0.2.2
 2 |   href: 0.2.2.md
 3 | 
 4 | - name: 0.2.1
 5 |   href: 0.2.1.md
 6 |   
 7 | - name: 0.2.0
 8 |   href: 0.2.0.md
 9 |   
10 | - name: 0.1.0
11 |   href: 0.1.0.md
12 |   
13 | - name: 0.0.17
14 |   href: 0.0.17.md
15 | 
16 | - name: 0.0.16
17 |   href: 0.0.16.md
18 | 
19 | - name: 0.0.0 - 0.0.15
20 |   href: update.md
21 | 


--------------------------------------------------------------------------------
/dotnet/website/template/public/main.js:
--------------------------------------------------------------------------------
1 | export default {
2 |     iconLinks: [
3 |       {
4 |         icon: 'github',
5 |         href: 'https://github.com/microsoft/autogen',
6 |         title: 'GitHub'
7 |       }
8 |     ]
9 |   }


--------------------------------------------------------------------------------
/dotnet/website/toc.yml:
--------------------------------------------------------------------------------
 1 | - name: Docs
 2 |   href: articles/
 3 | 
 4 | - name: Tutorial
 5 |   href: tutorial/
 6 | 
 7 | - name: API Reference
 8 |   href: api/
 9 | 
10 | - name: Release Notes
11 |   href: release_note/
12 | 
13 | - name: Comparison between Python AutoGen and AutoGen.Net
14 |   href: articles/function-comparison-page-between-python-AutoGen-and-autogen.net.md
15 | 
16 | - name: Other Languages
17 |   dropdown: true
18 |   items:
19 |     - name: Python
20 |       href: https://microsoft.github.io/autogen/
21 | 


--------------------------------------------------------------------------------
/dotnet/website/tutorial/toc.yml:
--------------------------------------------------------------------------------
 1 | - name: Chat with an agent
 2 |   href: Chat-with-an-agent.md
 3 | 
 4 | - name: Image chat with agent
 5 |   href: Image-chat-with-agent.md
 6 | 
 7 | - name: Create agent with tools
 8 |   href: Create-agent-with-tools.md
 9 | 
10 | - name: Use AutoGen.Net agent as model in AG Studio
11 |   href: Use-AutoGen.Net-agent-as-model-in-AG-Studio.md


--------------------------------------------------------------------------------
/python/docs/src/_apidoc_templates/module.rst.jinja:
--------------------------------------------------------------------------------
1 | {%- if show_headings %}
2 | {{- basename | e | heading }}
3 | 
4 | {% endif -%}
5 | .. automodule:: {{ qualname }}
6 | {%- for option in automodule_options %}
7 |    :{{ option }}:
8 | {%- endfor %}
9 | 


--------------------------------------------------------------------------------
/python/docs/src/_static/banner-override.js:
--------------------------------------------------------------------------------
 1 | var version = DOCUMENTATION_OPTIONS.VERSION;
 2 | if (version === "stable") {
 3 |   var styles = `
 4 | #bd-header-version-warning {
 5 |   display: none;
 6 | }
 7 |   `
 8 |   var styleSheet = document.createElement("style")
 9 |   styleSheet.textContent = styles
10 |   document.head.appendChild(styleSheet)
11 | }


--------------------------------------------------------------------------------
/python/docs/src/_static/images/logo/favicon-16x16.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:b4a649cf9cca62edf0f4f6e4acf76981fb9b27399b4d598b22b189c92424f4ea
3 | size 434
4 | 


--------------------------------------------------------------------------------
/python/docs/src/_static/images/logo/favicon-32x32.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:a272fc4c4a508fd936c130a727728da6c773de710a5ae600d06fac06329e0f6d
3 | size 998
4 | 


--------------------------------------------------------------------------------
/python/docs/src/_static/images/logo/favicon-512x512.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:c1f90048923bdaa4e2eeb6ab70f3cc059dc706d43e7208f336102702fc231b81
3 | size 45618
4 | 


--------------------------------------------------------------------------------
/python/docs/src/_static/images/logo/favicon.ico:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/python/docs/src/_static/images/logo/favicon.ico


--------------------------------------------------------------------------------
/python/docs/src/_static/switcher.json:
--------------------------------------------------------------------------------
 1 | [
 2 |   {
 3 |     "name": "v0.2 (stable)",
 4 |     "version": "0.2",
 5 |     "url": "https://microsoft.github.io/autogen/0.2/"
 6 |   },
 7 |   {
 8 |     "version": "dev",
 9 |     "url": "https://microsoft.github.io/autogen/dev/"
10 |   }
11 | ]
12 | 


--------------------------------------------------------------------------------
/python/docs/src/_templates/edit-this-page.html:
--------------------------------------------------------------------------------
 1 | {% if sourcename is defined and theme_use_edit_page_button and page_source_suffix %}
 2 |   {% set src = sourcename.split('.') %}
 3 |   <div class="tocsection editthispage">
 4 |     <a href="{{ to_main(get_edit_provider_and_url()[1]) }}">
 5 |       <i class="fa-solid fa-pencil"></i>
 6 |       {% set provider = get_edit_provider_and_url()[0] %}
 7 |       {% block edit_this_page_text %}
 8 |         {% if provider %}
 9 |           {% trans provider=provider %}Edit on {{ provider }}{% endtrans %}
10 |         {% else %}
11 |           {% trans %}Edit{% endtrans %}
12 |         {% endif %}
13 |       {% endblock %}
14 |     </a>
15 |   </div>
16 | {% endif %}
17 | 


--------------------------------------------------------------------------------
/python/docs/src/_templates/footer-middle-links.html:
--------------------------------------------------------------------------------
1 | <p><a href="https://go.microsoft.com/fwlink/?LinkId=521839">Privacy Policy</a> | <a href="https://go.microsoft.com/fwlink/?linkid=2259814">Consumer Health Privacy</a> </p>


--------------------------------------------------------------------------------
/python/docs/src/_templates/sidebar-nav-bs.html:
--------------------------------------------------------------------------------
 1 | {# Displays the TOC-subtree for pages nested under the currently active top-level TOCtree element. #}
 2 | <nav class="bd-docs-nav bd-links"
 3 |      aria-label="{{ _('Section Navigation') }}">
 4 |   <div class="bd-toc-item navbar-nav">
 5 |     {{- generate_toctree_html(
 6 |       "sidebar",
 7 |       show_nav_level=theme_show_nav_level | int,
 8 |       maxdepth=theme_navigation_depth | int,
 9 |       collapse=theme_collapse_navigation | tobool,
10 |       includehidden=theme_sidebar_includehidden | tobool,
11 |       titles_only=True
12 |       )
13 |     -}}
14 |   </div>
15 | </nav>


--------------------------------------------------------------------------------
/python/docs/src/_templates/theme-switcher.html:
--------------------------------------------------------------------------------
1 | {# Displays an icon to switch between light mode, dark mode, and auto (use browser's setting). #}
2 | {# As the theme switcher will only work when JavaScript is enabled, we hide it with `pst-js-only`. #}
3 | <button class="btn btn-sm nav-link pst-navbar-icon theme-switch-button pst-js-only" aria-label="{{ _('Color mode') }}" data-bs-title="{{ _('Color mode') }}"  data-bs-placement="bottom" data-bs-toggle="tooltip">
4 |   <i class="theme-switch fa-solid fa-sun                fa-lg" data-mode="light" title="{{ _('Light') }}"></i>
5 |   <i class="theme-switch fa-solid fa-moon               fa-lg" data-mode="dark"  title="{{ _('Dark') }}"></i>
6 |   <i class="theme-switch fa-solid fa-circle-half-stroke fa-lg" data-mode="auto"  title="{{ _('System Settings') }}"></i>
7 | </button>


--------------------------------------------------------------------------------
/python/docs/src/_templates/version-banner-override.html:
--------------------------------------------------------------------------------
1 | <script src="_static/banner-override.js"></script>


--------------------------------------------------------------------------------
/python/docs/src/images/autogen-magentic-one-agents.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:25a3a1f79319b89d80b8459af8b522eb9a884dea842b11e3d7dae2bca30add5e
3 | size 90181
4 | 


--------------------------------------------------------------------------------
/python/docs/src/images/autogen-magentic-one-example.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:fc910bda7e5f3b54d6502f26384f7b10b67f0597d7ac4631dfb45801882768fa
3 | size 201460
4 | 


--------------------------------------------------------------------------------
/python/docs/src/images/example-company.jpg:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:f487409436d338efe69d2e6aab69d7ac786321e215136b2d18736031bf5028ae
3 | size 112131
4 | 


--------------------------------------------------------------------------------
/python/docs/src/images/example-literature.jpg:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:a450a2917e21ee9d643e4c6bf7fee62fadd2e654772492ce821ac467ac6ad195
3 | size 31965
4 | 


--------------------------------------------------------------------------------
/python/docs/src/images/example-travel.jpeg:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:33c5749af8ebeb72d6020a147baebb3b801a14502d1c2d299dbe892d9ac5d8e0
3 | size 10894
4 | 


--------------------------------------------------------------------------------
/python/docs/src/images/open-ai-telemetry-example.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:96c0f435a6fc683b705db71b471281c5bbd8b7cf498894f43c491d6bb8c34711
3 | size 528018
4 | 


--------------------------------------------------------------------------------
/python/docs/src/user-guide/agentchat-user-guide/jaeger.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:d0e3f50140f8bef32e2f626792490b2c1c4728e5ec10130241cf3f49ada44a20
3 | size 167573
4 | 


--------------------------------------------------------------------------------
/python/docs/src/user-guide/agentchat-user-guide/tutorial/.gitignore:
--------------------------------------------------------------------------------
1 | coding


--------------------------------------------------------------------------------
/python/docs/src/user-guide/autogenstudio-user-guide/jsoneditor.jpg:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:afa594c040c6f8e342bb4ebd4a140e4e8cdd7291f01025f467c44d75acc52dad
3 | size 758268
4 | 


--------------------------------------------------------------------------------
/python/docs/src/user-guide/autogenstudio-user-guide/teambuilder.jpg:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:2d3c49bf0e8931375ab20cb1bf8eb5d8682c1a12b9609b8c0b993d1ae76f70ec
3 | size 734326
4 | 


--------------------------------------------------------------------------------
/python/docs/src/user-guide/core-user-guide/cookbook/index.md:
--------------------------------------------------------------------------------
 1 | # Cookbook
 2 | 
 3 | This section contains a collection of recipes that demonstrate how to use the Core API features.
 4 | 
 5 | ## List of recipes
 6 | 
 7 | ```{toctree}
 8 | :maxdepth: 1
 9 | 
10 | azure-openai-with-aad-auth
11 | termination-with-intervention
12 | tool-use-with-intervention
13 | extracting-results-with-an-agent
14 | openai-assistant-agent
15 | langgraph-agent
16 | llamaindex-agent
17 | local-llms-ollama-litellm
18 | instrumenting
19 | topic-subscription-scenarios
20 | structured-output-agent
21 | llm-usage-logger
22 | ```
23 | 


--------------------------------------------------------------------------------
/python/packages/agbench/.gitignore:
--------------------------------------------------------------------------------
1 | scenarios/*/Downloads
2 | scenarios/*/Tasks
3 | */Results


--------------------------------------------------------------------------------
/python/packages/agbench/MANIFEST.in:
--------------------------------------------------------------------------------
1 | recursive-exclude  scenarios *
2 | recursive-exclude  results *
3 | recursive-exclude  tests *
4 | recursive-exclude  utils *
5 | 


--------------------------------------------------------------------------------
/python/packages/agbench/benchmarks/.gitignore:
--------------------------------------------------------------------------------
1 | */Results/
2 | */Tasks/
3 | */Downloads/
4 | */ENV.json


--------------------------------------------------------------------------------
/python/packages/agbench/benchmarks/GAIA/.gitignore:
--------------------------------------------------------------------------------
1 | data
2 | gaia_validation_TeamOne
3 | *_results.csv
4 | results.csv
5 | ENV.json


--------------------------------------------------------------------------------
/python/packages/agbench/benchmarks/GAIA/Templates/MagenticOne/expected_answer.txt:
--------------------------------------------------------------------------------
1 | __EXPECTED_ANSWER__
2 | 


--------------------------------------------------------------------------------
/python/packages/agbench/benchmarks/GAIA/Templates/MagenticOne/prompt.txt:
--------------------------------------------------------------------------------
1 | __PROMPT__
2 | 


--------------------------------------------------------------------------------
/python/packages/agbench/benchmarks/GAIA/Templates/MagenticOne/requirements.txt:
--------------------------------------------------------------------------------
1 | tiktoken
2 | pyyaml
3 | /autogen_python/packages/autogen-core
4 | /autogen_python/packages/autogen-ext[openai,magentic-one]
5 | /autogen_python/packages/autogen-agentchat
6 | 


--------------------------------------------------------------------------------
/python/packages/agbench/benchmarks/GAIA/Templates/ParallelAgents/expected_answer.txt:
--------------------------------------------------------------------------------
1 | __EXPECTED_ANSWER__
2 | 


--------------------------------------------------------------------------------
/python/packages/agbench/benchmarks/GAIA/Templates/ParallelAgents/prompt.txt:
--------------------------------------------------------------------------------
1 | __PROMPT__
2 | 


--------------------------------------------------------------------------------
/python/packages/agbench/benchmarks/GAIA/Templates/ParallelAgents/requirements.txt:
--------------------------------------------------------------------------------
1 | tiktoken
2 | pyyaml
3 | /autogen_python/packages/autogen-core
4 | /autogen_python/packages/autogen-ext[openai,magentic-one]
5 | /autogen_python/packages/autogen-agentchat
6 | 


--------------------------------------------------------------------------------
/python/packages/agbench/benchmarks/GAIA/Templates/SelectorGroupChat/expected_answer.txt:
--------------------------------------------------------------------------------
1 | __EXPECTED_ANSWER__
2 | 


--------------------------------------------------------------------------------
/python/packages/agbench/benchmarks/GAIA/Templates/SelectorGroupChat/prompt.txt:
--------------------------------------------------------------------------------
1 | __PROMPT__
2 | 


--------------------------------------------------------------------------------
/python/packages/agbench/benchmarks/GAIA/Templates/SelectorGroupChat/requirements.txt:
--------------------------------------------------------------------------------
1 | tiktoken
2 | pyyaml
3 | /autogen_python/packages/autogen-core
4 | /autogen_python/packages/autogen-ext[openai,magentic-one]
5 | /autogen_python/packages/autogen-agentchat
6 | 


--------------------------------------------------------------------------------
/python/packages/agbench/benchmarks/HumanEval/Scripts/custom_tabulate.py:
--------------------------------------------------------------------------------
 1 | import os
 2 | import sys
 3 | 
 4 | from agbench.tabulate_cmd import default_tabulate
 5 | 
 6 | 
 7 | def main(args):
 8 |     default_tabulate(args)
 9 | 
10 | 
11 | if __name__ == "__main__" and __package__ is None:
12 |     main(sys.argv)
13 | 


--------------------------------------------------------------------------------
/python/packages/agbench/benchmarks/HumanEval/Templates/AgentChat/prompt.txt:
--------------------------------------------------------------------------------
1 | __PROMPT__
2 | 


--------------------------------------------------------------------------------
/python/packages/agbench/benchmarks/HumanEval/Templates/AgentChat/reasoning_model_context.py:
--------------------------------------------------------------------------------
 1 | from typing import List
 2 | from autogen_core.model_context import UnboundedChatCompletionContext
 3 | from autogen_core.models import AssistantMessage, LLMMessage
 4 | 
 5 | 
 6 | class ReasoningModelContext(UnboundedChatCompletionContext):
 7 |     """A model context for reasoning models."""
 8 | 
 9 |     async def get_messages(self) -> List[LLMMessage]:
10 |         messages = await super().get_messages()
11 |         # Filter out thought field from AssistantMessage.
12 |         messages_out = []
13 |         for message in messages:
14 |             if isinstance(message, AssistantMessage):
15 |                 message.thought = None
16 |             messages_out.append(message)
17 |         return messages_out


--------------------------------------------------------------------------------
/python/packages/agbench/benchmarks/HumanEval/Templates/AgentChat/requirements.txt:
--------------------------------------------------------------------------------
1 | pyyaml
2 | /autogen_python/packages/autogen-core
3 | /autogen_python/packages/autogen-ext[openai]
4 | /autogen_python/packages/autogen-agentchat
5 | 


--------------------------------------------------------------------------------
/python/packages/agbench/benchmarks/HumanEval/Templates/AgentChat/test.txt:
--------------------------------------------------------------------------------
1 | __TEST__
2 | 


--------------------------------------------------------------------------------
/python/packages/agbench/setup.py:
--------------------------------------------------------------------------------
1 | from setuptools import setup
2 | 
3 | setup()
4 | 


--------------------------------------------------------------------------------
/python/packages/agbench/src/agbench/__init__.py:
--------------------------------------------------------------------------------
1 | from .version import __version__
2 | 


--------------------------------------------------------------------------------
/python/packages/agbench/src/agbench/__main__.py:
--------------------------------------------------------------------------------
1 | from .cli import main
2 | 
3 | if __name__ == "__main__":
4 |     main()
5 | 


--------------------------------------------------------------------------------
/python/packages/agbench/src/agbench/linter/__init__.py:
--------------------------------------------------------------------------------
1 | # __init__.py
2 | from ._base import BaseQualitativeCoder, Code, CodedDocument, Document
3 | 
4 | __all__ = ["Code", "Document", "CodedDocument", "BaseQualitativeCoder"]
5 | 


--------------------------------------------------------------------------------
/python/packages/agbench/src/agbench/linter/coders/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/python/packages/agbench/src/agbench/linter/coders/__init__.py


--------------------------------------------------------------------------------
/python/packages/agbench/src/agbench/load_module.py:
--------------------------------------------------------------------------------
 1 | import importlib.util
 2 | import os
 3 | import sys
 4 | from types import ModuleType
 5 | 
 6 | 
 7 | def load_module(module_path: str) -> ModuleType:
 8 |     module_name = os.path.basename(module_path).replace(".py", "")
 9 |     spec = importlib.util.spec_from_file_location(module_name, module_path)
10 |     if spec is None:
11 |         raise ValueError(f"Could not load module from path: {module_path}")
12 |     module = importlib.util.module_from_spec(spec)
13 |     sys.modules[module_name] = module
14 |     assert spec.loader is not None
15 |     spec.loader.exec_module(module)
16 |     return module
17 | 


--------------------------------------------------------------------------------
/python/packages/agbench/src/agbench/template/global_finalize.sh:
--------------------------------------------------------------------------------
1 | # Global finalize.
2 | 


--------------------------------------------------------------------------------
/python/packages/agbench/src/agbench/template/global_init.sh:
--------------------------------------------------------------------------------
1 | echo AUTOGEN_TESTBED_SETTING: [$AUTOGEN_TESTBED_SETTING]
2 | 


--------------------------------------------------------------------------------
/python/packages/agbench/src/agbench/template/requirements.txt:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/python/packages/agbench/src/agbench/template/requirements.txt


--------------------------------------------------------------------------------
/python/packages/agbench/src/agbench/version.py:
--------------------------------------------------------------------------------
1 | __version__ = "0.0.1a1"
2 | 


--------------------------------------------------------------------------------
/python/packages/autogen-agentchat/src/autogen_agentchat/__init__.py:
--------------------------------------------------------------------------------
 1 | """
 2 | This module provides the main entry point for the autogen_agentchat package.
 3 | It includes logger names for trace and event logs, and retrieves the package version.
 4 | """
 5 | 
 6 | import importlib.metadata
 7 | 
 8 | TRACE_LOGGER_NAME = "autogen_agentchat"
 9 | """Logger name for trace logs."""
10 | 
11 | EVENT_LOGGER_NAME = "autogen_agentchat.events"
12 | """Logger name for event logs."""
13 | 
14 | __version__ = importlib.metadata.version("autogen_agentchat")
15 | 


--------------------------------------------------------------------------------
/python/packages/autogen-agentchat/src/autogen_agentchat/base/__init__.py:
--------------------------------------------------------------------------------
 1 | from ._chat_agent import ChatAgent, Response
 2 | from ._handoff import Handoff
 3 | from ._task import TaskResult, TaskRunner
 4 | from ._team import Team
 5 | from ._termination import AndTerminationCondition, OrTerminationCondition, TerminatedException, TerminationCondition
 6 | 
 7 | __all__ = [
 8 |     "ChatAgent",
 9 |     "Response",
10 |     "Team",
11 |     "TerminatedException",
12 |     "TerminationCondition",
13 |     "AndTerminationCondition",
14 |     "OrTerminationCondition",
15 |     "TaskResult",
16 |     "TaskRunner",
17 |     "Handoff",
18 | ]
19 | 


--------------------------------------------------------------------------------
/python/packages/autogen-agentchat/src/autogen_agentchat/py.typed:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/python/packages/autogen-agentchat/src/autogen_agentchat/py.typed


--------------------------------------------------------------------------------
/python/packages/autogen-agentchat/src/autogen_agentchat/teams/_group_chat/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/python/packages/autogen-agentchat/src/autogen_agentchat/teams/_group_chat/__init__.py


--------------------------------------------------------------------------------
/python/packages/autogen-agentchat/src/autogen_agentchat/teams/_group_chat/_graph/__init__.py:
--------------------------------------------------------------------------------
 1 | from ._digraph_group_chat import (
 2 |     DiGraph,
 3 |     DiGraphEdge,
 4 |     DiGraphNode,
 5 |     GraphFlow,
 6 |     GraphFlowManager,
 7 | )
 8 | from ._graph_builder import DiGraphBuilder
 9 | 
10 | __all__ = [
11 |     "GraphFlow",
12 |     "DiGraph",
13 |     "GraphFlowManager",
14 |     "DiGraphNode",
15 |     "DiGraphEdge",
16 |     "DiGraphBuilder",
17 | ]
18 | 


--------------------------------------------------------------------------------
/python/packages/autogen-agentchat/src/autogen_agentchat/teams/_group_chat/_magentic_one/__init__.py:
--------------------------------------------------------------------------------
1 | from ._magentic_one_group_chat import MagenticOneGroupChat
2 | 
3 | __all__ = [
4 |     "MagenticOneGroupChat",
5 | ]
6 | 


--------------------------------------------------------------------------------
/python/packages/autogen-agentchat/src/autogen_agentchat/tools/__init__.py:
--------------------------------------------------------------------------------
1 | from ._agent import AgentTool
2 | from ._team import TeamTool
3 | 
4 | __all__ = ["AgentTool", "TeamTool"]
5 | 


--------------------------------------------------------------------------------
/python/packages/autogen-agentchat/src/autogen_agentchat/ui/__init__.py:
--------------------------------------------------------------------------------
1 | """
2 | This module implements utility classes for formatting/printing agent messages.
3 | """
4 | 
5 | from ._console import Console, UserInputManager
6 | 
7 | __all__ = ["Console", "UserInputManager"]
8 | 


--------------------------------------------------------------------------------
/python/packages/autogen-agentchat/src/autogen_agentchat/utils/__init__.py:
--------------------------------------------------------------------------------
1 | """
2 | This module implements various utilities common to AgentChat agents and teams.
3 | """
4 | 
5 | from ._utils import content_to_str, remove_images
6 | 
7 | __all__ = ["content_to_str", "remove_images"]
8 | 


--------------------------------------------------------------------------------
/python/packages/autogen-core/README.md:
--------------------------------------------------------------------------------
1 | # AutoGen Core
2 | 
3 | - [Documentation](https://microsoft.github.io/autogen/stable/user-guide/core-user-guide/index.html)
4 | 
5 | AutoGen core offers an easy way to quickly build event-driven, distributed, scalable, resilient AI agent systems. Agents are developed by using the [Actor model](https://en.wikipedia.org/wiki/Actor_model). You can build and run your agent system locally and easily move to a distributed system in the cloud when you are ready.
6 | 


--------------------------------------------------------------------------------
/python/packages/autogen-core/src/autogen_core/_agent_metadata.py:
--------------------------------------------------------------------------------
1 | from typing import TypedDict
2 | 
3 | 
4 | class AgentMetadata(TypedDict):
5 |     type: str
6 |     key: str
7 |     description: str
8 | 


--------------------------------------------------------------------------------
/python/packages/autogen-core/src/autogen_core/_agent_type.py:
--------------------------------------------------------------------------------
1 | from dataclasses import dataclass
2 | 
3 | 
4 | @dataclass(eq=True, frozen=True)
5 | class AgentType:
6 |     type: str
7 |     """String representation of this agent type."""
8 | 


--------------------------------------------------------------------------------
/python/packages/autogen-core/src/autogen_core/_constants.py:
--------------------------------------------------------------------------------
 1 | ROOT_LOGGER_NAME = "autogen_core"
 2 | """str: Logger name used for root logger"""
 3 | 
 4 | EVENT_LOGGER_NAME = "autogen_core.events"
 5 | """str: Logger name used for structured event logging"""
 6 | 
 7 | 
 8 | TRACE_LOGGER_NAME = "autogen_core.trace"
 9 | """str: Logger name used for developer intended trace logging. The content and format of this log should not be depended upon."""
10 | 


--------------------------------------------------------------------------------
/python/packages/autogen-core/src/autogen_core/_message_context.py:
--------------------------------------------------------------------------------
 1 | from dataclasses import dataclass
 2 | 
 3 | from ._agent_id import AgentId
 4 | from ._cancellation_token import CancellationToken
 5 | from ._topic import TopicId
 6 | 
 7 | 
 8 | @dataclass
 9 | class MessageContext:
10 |     sender: AgentId | None
11 |     topic_id: TopicId | None
12 |     is_rpc: bool
13 |     cancellation_token: CancellationToken
14 |     message_id: str
15 | 


--------------------------------------------------------------------------------
/python/packages/autogen-core/src/autogen_core/_telemetry/__init__.py:
--------------------------------------------------------------------------------
 1 | from ._genai import (
 2 |     trace_create_agent_span,
 3 |     trace_invoke_agent_span,
 4 |     trace_tool_span,
 5 | )
 6 | from ._propagation import (
 7 |     EnvelopeMetadata,
 8 |     TelemetryMetadataContainer,
 9 |     get_telemetry_envelope_metadata,
10 |     get_telemetry_grpc_metadata,
11 | )
12 | from ._tracing import TraceHelper
13 | from ._tracing_config import MessageRuntimeTracingConfig
14 | 
15 | __all__ = [
16 |     "EnvelopeMetadata",
17 |     "get_telemetry_envelope_metadata",
18 |     "get_telemetry_grpc_metadata",
19 |     "TelemetryMetadataContainer",
20 |     "TraceHelper",
21 |     "MessageRuntimeTracingConfig",
22 |     "trace_create_agent_span",
23 |     "trace_invoke_agent_span",
24 |     "trace_tool_span",
25 | ]
26 | 


--------------------------------------------------------------------------------
/python/packages/autogen-core/src/autogen_core/_telemetry/_constants.py:
--------------------------------------------------------------------------------
1 | NAMESPACE = "autogen"
2 | 


--------------------------------------------------------------------------------
/python/packages/autogen-core/src/autogen_core/_types.py:
--------------------------------------------------------------------------------
 1 | from __future__ import annotations
 2 | 
 3 | from dataclasses import dataclass
 4 | 
 5 | 
 6 | @dataclass
 7 | class FunctionCall:
 8 |     id: str
 9 |     # JSON args
10 |     arguments: str
11 |     # Function to call
12 |     name: str
13 | 


--------------------------------------------------------------------------------
/python/packages/autogen-core/src/autogen_core/code_executor/__init__.py:
--------------------------------------------------------------------------------
 1 | from ._base import CodeBlock, CodeExecutor, CodeResult
 2 | from ._func_with_reqs import (
 3 |     Alias,
 4 |     FunctionWithRequirements,
 5 |     FunctionWithRequirementsStr,
 6 |     Import,
 7 |     ImportFromModule,
 8 |     with_requirements,
 9 | )
10 | 
11 | __all__ = [
12 |     "CodeBlock",
13 |     "CodeExecutor",
14 |     "CodeResult",
15 |     "Alias",
16 |     "ImportFromModule",
17 |     "Import",
18 |     "FunctionWithRequirements",
19 |     "FunctionWithRequirementsStr",
20 |     "with_requirements",
21 | ]
22 | 


--------------------------------------------------------------------------------
/python/packages/autogen-core/src/autogen_core/exceptions.py:
--------------------------------------------------------------------------------
 1 | __all__ = ["CantHandleException", "UndeliverableException", "MessageDroppedException", "NotAccessibleError"]
 2 | 
 3 | 
 4 | class CantHandleException(Exception):
 5 |     """Raised when a handler can't handle the exception."""
 6 | 
 7 | 
 8 | class UndeliverableException(Exception):
 9 |     """Raised when a message can't be delivered."""
10 | 
11 | 
12 | class MessageDroppedException(Exception):
13 |     """Raised when a message is dropped."""
14 | 
15 | 
16 | class NotAccessibleError(Exception):
17 |     """Tried to access a value that is not accessible. For example if it is remote cannot be accessed locally."""
18 | 


--------------------------------------------------------------------------------
/python/packages/autogen-core/src/autogen_core/memory/__init__.py:
--------------------------------------------------------------------------------
 1 | from ._base_memory import Memory, MemoryContent, MemoryMimeType, MemoryQueryResult, UpdateContextResult
 2 | from ._list_memory import ListMemory
 3 | 
 4 | __all__ = [
 5 |     "Memory",
 6 |     "MemoryContent",
 7 |     "MemoryQueryResult",
 8 |     "UpdateContextResult",
 9 |     "MemoryMimeType",
10 |     "ListMemory",
11 | ]
12 | 


--------------------------------------------------------------------------------
/python/packages/autogen-core/src/autogen_core/model_context/__init__.py:
--------------------------------------------------------------------------------
 1 | from ._buffered_chat_completion_context import BufferedChatCompletionContext
 2 | from ._chat_completion_context import ChatCompletionContext, ChatCompletionContextState
 3 | from ._head_and_tail_chat_completion_context import HeadAndTailChatCompletionContext
 4 | from ._token_limited_chat_completion_context import TokenLimitedChatCompletionContext
 5 | from ._unbounded_chat_completion_context import (
 6 |     UnboundedChatCompletionContext,
 7 | )
 8 | 
 9 | __all__ = [
10 |     "ChatCompletionContext",
11 |     "ChatCompletionContextState",
12 |     "UnboundedChatCompletionContext",
13 |     "BufferedChatCompletionContext",
14 |     "TokenLimitedChatCompletionContext",
15 |     "HeadAndTailChatCompletionContext",
16 | ]
17 | 


--------------------------------------------------------------------------------
/python/packages/autogen-core/src/autogen_core/py.typed:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/python/packages/autogen-core/src/autogen_core/py.typed


--------------------------------------------------------------------------------
/python/packages/autogen-core/src/autogen_core/tool_agent/__init__.py:
--------------------------------------------------------------------------------
 1 | from ._caller_loop import tool_agent_caller_loop
 2 | from ._tool_agent import (
 3 |     InvalidToolArgumentsException,
 4 |     ToolAgent,
 5 |     ToolException,
 6 |     ToolExecutionException,
 7 |     ToolNotFoundException,
 8 | )
 9 | 
10 | __all__ = [
11 |     "ToolAgent",
12 |     "ToolException",
13 |     "ToolNotFoundException",
14 |     "InvalidToolArgumentsException",
15 |     "ToolExecutionException",
16 |     "tool_agent_caller_loop",
17 | ]
18 | 


--------------------------------------------------------------------------------
/python/packages/autogen-core/src/autogen_core/utils/__init__.py:
--------------------------------------------------------------------------------
1 | from ._json_to_pydantic import schema_to_pydantic_model
2 | from ._load_json import extract_json_from_str
3 | 
4 | __all__ = ["schema_to_pydantic_model", "extract_json_from_str"]
5 | 


--------------------------------------------------------------------------------
/python/packages/autogen-core/tests/protos/serialization_test.proto:
--------------------------------------------------------------------------------
 1 | syntax = "proto3";
 2 | 
 3 | package agents;
 4 | 
 5 | message ProtoMessage {
 6 |       string message = 1;
 7 | }
 8 | message NestingProtoMessage {
 9 |       string message = 1;
10 |       ProtoMessage nested = 2;
11 | }


--------------------------------------------------------------------------------
/python/packages/autogen-core/tests/protos/serialization_test_pb2_grpc.pyi:
--------------------------------------------------------------------------------
 1 | """
 2 | @generated by mypy-protobuf.  Do not edit manually!
 3 | isort:skip_file
 4 | """
 5 | 
 6 | import abc
 7 | import collections.abc
 8 | import grpc
 9 | import grpc.aio
10 | import typing
11 | 
12 | _T = typing.TypeVar("_T")
13 | 
14 | class _MaybeAsyncIterator(collections.abc.AsyncIterator[_T], collections.abc.Iterator[_T], metaclass=abc.ABCMeta): ...
15 | 
16 | class _ServicerContext(grpc.ServicerContext, grpc.aio.ServicerContext):  # type: ignore[misc, type-arg]
17 |     ...
18 | 


--------------------------------------------------------------------------------
/python/packages/autogen-core/tests/test_base_agent.py:
--------------------------------------------------------------------------------
 1 | import pytest
 2 | from autogen_core import AgentId, AgentInstantiationContext, AgentRuntime
 3 | from autogen_test_utils import NoopAgent
 4 | from pytest_mock import MockerFixture
 5 | 
 6 | 
 7 | @pytest.mark.asyncio
 8 | async def test_base_agent_create(mocker: MockerFixture) -> None:
 9 |     runtime = mocker.Mock(spec=AgentRuntime)
10 | 
11 |     # Shows how to set the context for the agent instantiation in a test context
12 |     with AgentInstantiationContext.populate_context((runtime, AgentId("name2", "namespace2"))):
13 |         agent2 = NoopAgent()
14 |         assert agent2.runtime == runtime
15 |         assert agent2.id == AgentId("name2", "namespace2")
16 | 


--------------------------------------------------------------------------------
/python/packages/autogen-core/tests/test_models.py:
--------------------------------------------------------------------------------
 1 | import pytest
 2 | from autogen_core.models import ModelInfo, validate_model_info
 3 | 
 4 | 
 5 | def test_model_info() -> None:
 6 |     # Valid model info.
 7 |     info: ModelInfo = {
 8 |         "family": "gpt-4o",
 9 |         "vision": True,
10 |         "function_calling": True,
11 |         "json_output": True,
12 |         "structured_output": True,
13 |     }
14 |     validate_model_info(info)
15 | 
16 |     # Invalid model info.
17 |     info = {
18 |         "family": "gpt-4o",
19 |         "vision": True,
20 |         "function_calling": True,
21 |     }  # type: ignore
22 |     with pytest.raises(ValueError):
23 |         validate_model_info(info)
24 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/README.md:
--------------------------------------------------------------------------------
1 | # AutoGen Extensions
2 | 
3 | - [Documentation](https://microsoft.github.io/autogen/stable/user-guide/extensions-user-guide/index.html)
4 | 
5 | AutoGen is designed to be extensible. The `autogen-ext` package contains many different component implementations maintained by the AutoGen project. However, we strongly encourage others to build their own components and publish them as part of the ecosytem.
6 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/conftest.py:
--------------------------------------------------------------------------------
 1 | import pytest
 2 | 
 3 | def pytest_addoption(parser):
 4 |     parser.addoption(
 5 |         "--grpc", action="store_true", default=False, help="run grpc tests"
 6 |     )
 7 | 
 8 | def pytest_collection_modifyitems(config, items):
 9 |     grpc_option_passed = config.getoption("--grpc")
10 |     skip_grpc = pytest.mark.skip(reason="Need --grpc option to run")
11 |     skip_non_grpc = pytest.mark.skip(reason="Skipped since --grpc passed")
12 | 
13 |     for item in items:
14 |         if "grpc" in item.keywords and not grpc_option_passed:
15 |             item.add_marker(skip_grpc)
16 |         elif "grpc" not in item.keywords and grpc_option_passed:
17 |             item.add_marker(skip_non_grpc)
18 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/imgs/task_centric_memory.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:a9d5d3cdaa77c863ecbeec41ce988c1018d49b2e914a9b3775f6574ea4bbbcee
3 | size 37076
4 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/imgs/task_centric_memory_2.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:119f7baf93e71fee417d1a9f9f994f6b3d4fbbc5aae930096a6897e755167e61
3 | size 28253
4 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/imgs/task_centric_memory_3.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:e2af80416085182ba099e5094014f37b7f88daf972dce704d862540566a52bb9
3 | size 30082
4 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/__init__.py:
--------------------------------------------------------------------------------
1 | import importlib.metadata
2 | 
3 | __version__ = importlib.metadata.version("autogen_ext")
4 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/agents/azure/__init__.py:
--------------------------------------------------------------------------------
 1 | try:
 2 |     from ._azure_ai_agent import AzureAIAgent
 3 | except ImportError as e:
 4 |     raise ImportError(
 5 |         "Dependencies for AzureAIAgent not found. "
 6 |         'Please install autogen-ext with the "azure" extra: '
 7 |         'pip install "autogen-ext[azure]"'
 8 |     ) from e
 9 | 
10 | __all__ = ["AzureAIAgent"]
11 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/agents/file_surfer/__init__.py:
--------------------------------------------------------------------------------
1 | from ._file_surfer import FileSurfer
2 | 
3 | __all__ = ["FileSurfer"]
4 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/agents/magentic_one/__init__.py:
--------------------------------------------------------------------------------
 1 | try:
 2 |     from ._magentic_one_coder_agent import MagenticOneCoderAgent
 3 | except ImportError as e:
 4 |     raise ImportError(
 5 |         "Dependencies for MagenticOneCoderAgent not found. "
 6 |         'Please install autogen-ext with the "magentic-one" extra: '
 7 |         'pip install "autogen-ext[magentic-one]"'
 8 |     ) from e
 9 | 
10 | __all__ = ["MagenticOneCoderAgent"]
11 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/agents/openai/__init__.py:
--------------------------------------------------------------------------------
 1 | try:
 2 |     from ._openai_agent import OpenAIAgent
 3 |     from ._openai_assistant_agent import OpenAIAssistantAgent
 4 | except ImportError as e:
 5 |     raise ImportError(
 6 |         "Dependencies for OpenAI agents not found. "
 7 |         'Please install autogen-ext with the "openai" extra: '
 8 |         'pip install "autogen-ext[openai]"'
 9 |     ) from e
10 | 
11 | __all__ = ["OpenAIAssistantAgent", "OpenAIAgent"]
12 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/agents/video_surfer/__init__.py:
--------------------------------------------------------------------------------
1 | from ._video_surfer import VideoSurfer
2 | 
3 | __all__ = ["VideoSurfer"]
4 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/agents/web_surfer/__init__.py:
--------------------------------------------------------------------------------
1 | from ._multimodal_web_surfer import MultimodalWebSurfer
2 | from .playwright_controller import PlaywrightController
3 | 
4 | __all__ = ["MultimodalWebSurfer", "PlaywrightController"]
5 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/agents/web_surfer/_events.py:
--------------------------------------------------------------------------------
 1 | from dataclasses import dataclass
 2 | from typing import Any, Dict
 3 | 
 4 | 
 5 | @dataclass
 6 | class WebSurferEvent:
 7 |     source: str
 8 |     message: str
 9 |     url: str
10 |     action: str | None = None
11 |     arguments: Dict[str, Any] | None = None
12 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/cache_store/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/python/packages/autogen-ext/src/autogen_ext/cache_store/__init__.py


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/code_executors/azure/__init__.py:
--------------------------------------------------------------------------------
1 | from ._azure_container_code_executor import ACADynamicSessionsCodeExecutor, TokenProvider
2 | 
3 | __all__ = ["TokenProvider", "ACADynamicSessionsCodeExecutor"]
4 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/code_executors/docker/__init__.py:
--------------------------------------------------------------------------------
1 | from ._docker_code_executor import DockerCommandLineCodeExecutor
2 | 
3 | __all__ = ["DockerCommandLineCodeExecutor"]
4 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/code_executors/docker_jupyter/__init__.py:
--------------------------------------------------------------------------------
 1 | from ._docker_jupyter import DockerJupyterCodeExecutor, DockerJupyterCodeResult
 2 | from ._jupyter_server import DockerJupyterServer, JupyterClient, JupyterKernelClient
 3 | 
 4 | __all__ = [
 5 |     "DockerJupyterCodeExecutor",
 6 |     "DockerJupyterServer",
 7 |     "JupyterClient",
 8 |     "JupyterKernelClient",
 9 |     "DockerJupyterCodeResult",
10 | ]
11 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/code_executors/jupyter/__init__.py:
--------------------------------------------------------------------------------
1 | from ._jupyter_code_executor import JupyterCodeExecutor, JupyterCodeResult
2 | 
3 | __all__ = [
4 |     "JupyterCodeExecutor",
5 |     "JupyterCodeResult",
6 | ]
7 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/experimental/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/python/packages/autogen-ext/src/autogen_ext/experimental/__init__.py


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/experimental/task_centric_memory/__init__.py:
--------------------------------------------------------------------------------
1 | from ._memory_bank import MemoryBankConfig
2 | from .memory_controller import MemoryController, MemoryControllerConfig
3 | 
4 | __all__ = ["MemoryController", "MemoryControllerConfig", "MemoryBankConfig"]
5 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/experimental/task_centric_memory/utils/__init__.py:
--------------------------------------------------------------------------------
 1 | from .apprentice import Apprentice, ApprenticeConfig
 2 | from .chat_completion_client_recorder import ChatCompletionClientRecorder
 3 | from .grader import Grader
 4 | from .page_logger import PageLogger, PageLoggerConfig
 5 | from .teachability import Teachability
 6 | 
 7 | __all__ = [
 8 |     "Apprentice",
 9 |     "ChatCompletionClientRecorder",
10 |     "Grader",
11 |     "PageLogger",
12 |     "Teachability",
13 |     "ApprenticeConfig",
14 |     "PageLoggerConfig",
15 | ]
16 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/memory/__init__.py:
--------------------------------------------------------------------------------
1 | 
2 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/memory/canvas/__init__.py:
--------------------------------------------------------------------------------
1 | from ._text_canvas import TextCanvas
2 | from ._text_canvas_memory import TextCanvasMemory
3 | 
4 | __all__ = ["TextCanvas", "TextCanvasMemory"]
5 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/memory/mem0/__init__.py:
--------------------------------------------------------------------------------
1 | from ._mem0 import Mem0Memory, Mem0MemoryConfig
2 | 
3 | __all__ = [
4 |     "Mem0Memory",
5 |     "Mem0MemoryConfig",
6 | ]
7 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/models/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/python/packages/autogen-ext/src/autogen_ext/models/__init__.py


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/models/_utils/normalize_stop_reason.py:
--------------------------------------------------------------------------------
 1 | from typing import Dict
 2 | 
 3 | from autogen_core.models import FinishReasons
 4 | 
 5 | 
 6 | def normalize_stop_reason(stop_reason: str | None) -> FinishReasons:
 7 |     if stop_reason is None:
 8 |         return "unknown"
 9 | 
10 |     # Convert to lower case
11 |     stop_reason = stop_reason.lower()
12 | 
13 |     KNOWN_STOP_MAPPINGS: Dict[str, FinishReasons] = {
14 |         "stop": "stop",
15 |         "length": "length",
16 |         "content_filter": "content_filter",
17 |         "function_calls": "function_calls",
18 |         "end_turn": "stop",
19 |         "tool_calls": "function_calls",
20 |     }
21 | 
22 |     return KNOWN_STOP_MAPPINGS.get(stop_reason, "unknown")
23 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/models/azure/__init__.py:
--------------------------------------------------------------------------------
1 | from ._azure_ai_client import AzureAIChatCompletionClient
2 | from .config import AzureAIChatCompletionClientConfig
3 | 
4 | __all__ = ["AzureAIChatCompletionClient", "AzureAIChatCompletionClientConfig"]
5 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/models/cache/__init__.py:
--------------------------------------------------------------------------------
1 | from ._chat_completion_cache import CHAT_CACHE_VALUE_TYPE, ChatCompletionCache
2 | 
3 | __all__ = [
4 |     "CHAT_CACHE_VALUE_TYPE",
5 |     "ChatCompletionCache",
6 | ]
7 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/models/llama_cpp/__init__.py:
--------------------------------------------------------------------------------
 1 | try:
 2 |     from ._llama_cpp_completion_client import LlamaCppChatCompletionClient
 3 | except ImportError as e:
 4 |     raise ImportError(
 5 |         "Dependencies for Llama Cpp not found. "
 6 |         "Please install llama-cpp-python: "
 7 |         "pip install autogen-ext[llama-cpp]"
 8 |     ) from e
 9 | 
10 | __all__ = ["LlamaCppChatCompletionClient"]
11 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/models/ollama/__init__.py:
--------------------------------------------------------------------------------
 1 | from ._ollama_client import OllamaChatCompletionClient
 2 | from .config import (
 3 |     BaseOllamaClientConfigurationConfigModel,
 4 |     CreateArgumentsConfigModel,
 5 | )
 6 | 
 7 | __all__ = [
 8 |     "OllamaChatCompletionClient",
 9 |     "BaseOllamaClientConfigurationConfigModel",
10 |     "CreateArgumentsConfigModel",
11 | ]
12 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/models/openai/_transformation/__init__.py:
--------------------------------------------------------------------------------
 1 | from .registry import (
 2 |     MESSAGE_TRANSFORMERS,
 3 |     build_conditional_transformer_func,
 4 |     build_transformer_func,
 5 |     get_transformer,
 6 |     register_transformer,
 7 | )
 8 | from .types import (
 9 |     LLMMessageContent,
10 |     MessageParam,
11 |     TransformerFunc,
12 |     TransformerMap,
13 |     TrasformerReturnType,
14 | )
15 | 
16 | __all__ = [
17 |     "register_transformer",
18 |     "get_transformer",
19 |     "build_transformer_func",
20 |     "build_conditional_transformer_func",
21 |     "MESSAGE_TRANSFORMERS",
22 |     "TransformerMap",
23 |     "TransformerFunc",
24 |     "MessageParam",
25 |     "LLMMessageContent",
26 |     "TrasformerReturnType",
27 | ]
28 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/models/openai/_utils.py:
--------------------------------------------------------------------------------
 1 | import re
 2 | 
 3 | 
 4 | def assert_valid_name(name: str) -> str:
 5 |     """
 6 |     Ensure that configured names are valid, raises ValueError if not.
 7 | 
 8 |     For munging LLM responses use _normalize_name to ensure LLM specified names don't break the API.
 9 |     """
10 |     if not re.match(r"^[a-zA-Z0-9_-]+
quot;, name):
11 |         raise ValueError(f"Invalid name: {name}. Only letters, numbers, '_' and '-' are allowed.")
12 |     if len(name) > 64:
13 |         raise ValueError(f"Invalid name: {name}. Name must be less than 64 characters.")
14 |     return name
15 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/models/replay/__init__.py:
--------------------------------------------------------------------------------
1 | from ._replay_chat_completion_client import ReplayChatCompletionClient
2 | 
3 | __all__ = [
4 |     "ReplayChatCompletionClient",
5 | ]
6 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/models/semantic_kernel/__init__.py:
--------------------------------------------------------------------------------
1 | from ._sk_chat_completion_adapter import SKChatCompletionAdapter
2 | 
3 | __all__ = ["SKChatCompletionAdapter"]
4 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/py.typed:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/python/packages/autogen-ext/src/autogen_ext/py.typed


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/runtimes/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/python/packages/autogen-ext/src/autogen_ext/runtimes/__init__.py


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/runtimes/grpc/__init__.py:
--------------------------------------------------------------------------------
 1 | from ._worker_runtime import GrpcWorkerAgentRuntime
 2 | from ._worker_runtime_host import GrpcWorkerAgentRuntimeHost
 3 | from ._worker_runtime_host_servicer import GrpcWorkerAgentRuntimeHostServicer
 4 | 
 5 | try:
 6 |     import grpc  # type: ignore
 7 | except ImportError as e:
 8 |     raise ImportError(
 9 |         "To use the GRPC runtime the grpc extra must be installed. Run `pip install autogen-ext[grpc]`"
10 |     ) from e
11 | 
12 | __all__ = [
13 |     "GrpcWorkerAgentRuntime",
14 |     "GrpcWorkerAgentRuntimeHost",
15 |     "GrpcWorkerAgentRuntimeHostServicer",
16 | ]
17 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/runtimes/grpc/_constants.py:
--------------------------------------------------------------------------------
 1 | GRPC_IMPORT_ERROR_STR = (
 2 |     "Distributed runtime features require additional dependencies. Install them with: pip install autogen-core[grpc]"
 3 | )
 4 | 
 5 | DATA_CONTENT_TYPE_ATTR = "datacontenttype"
 6 | DATA_SCHEMA_ATTR = "dataschema"
 7 | AGENT_SENDER_TYPE_ATTR = "agagentsendertype"
 8 | AGENT_SENDER_KEY_ATTR = "agagentsenderkey"
 9 | MESSAGE_KIND_ATTR = "agmsgkind"
10 | MESSAGE_KIND_VALUE_PUBLISH = "publish"
11 | MESSAGE_KIND_VALUE_RPC_REQUEST = "rpc_request"
12 | MESSAGE_KIND_VALUE_RPC_RESPONSE = "rpc_response"
13 | MESSAGE_KIND_VALUE_RPC_ERROR = "error"
14 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/runtimes/grpc/_type_helpers.py:
--------------------------------------------------------------------------------
1 | from typing import Any, Sequence, Tuple
2 | 
3 | # Had to redefine this from grpc.aio._typing as using that one was causing mypy errors
4 | ChannelArgumentType = Sequence[Tuple[str, Any]]
5 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/runtimes/grpc/protos/__init__.py:
--------------------------------------------------------------------------------
1 | """
2 | The :mod:`autogen_ext.runtimes.grpc.protos` module provides Google Protobuf classes for agent-worker communication
3 | """
4 | 
5 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/teams/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/python/packages/autogen-ext/src/autogen_ext/teams/__init__.py


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/tools/azure/__init__.py:
--------------------------------------------------------------------------------
 1 | from ._ai_search import (
 2 |     AzureAISearchTool,
 3 |     BaseAzureAISearchTool,
 4 |     SearchQuery,
 5 |     SearchResult,
 6 |     SearchResults,
 7 |     VectorizableTextQuery,
 8 | )
 9 | from ._config import AzureAISearchConfig
10 | 
11 | __all__ = [
12 |     "AzureAISearchTool",
13 |     "BaseAzureAISearchTool",
14 |     "SearchQuery",
15 |     "SearchResult",
16 |     "SearchResults",
17 |     "AzureAISearchConfig",
18 |     "VectorizableTextQuery",
19 | ]
20 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/tools/code_execution/__init__.py:
--------------------------------------------------------------------------------
1 | from ._code_execution import CodeExecutionInput, CodeExecutionResult, PythonCodeExecutionTool
2 | 
3 | __all__ = ["CodeExecutionInput", "CodeExecutionResult", "PythonCodeExecutionTool"]
4 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/tools/http/__init__.py:
--------------------------------------------------------------------------------
1 | from ._http_tool import HttpTool
2 | 
3 | __all__ = ["HttpTool"]
4 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/tools/langchain/__init__.py:
--------------------------------------------------------------------------------
1 | from ._langchain_adapter import LangChainToolAdapter
2 | 
3 | __all__ = ["LangChainToolAdapter"]
4 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/tools/semantic_kernel/__init__.py:
--------------------------------------------------------------------------------
1 | from ._kernel_function_from_tool import KernelFunctionFromTool, KernelFunctionFromToolSchema
2 | 
3 | __all__ = [
4 |     "KernelFunctionFromTool",
5 |     "KernelFunctionFromToolSchema",
6 | ]
7 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/src/autogen_ext/ui/__init__.py:
--------------------------------------------------------------------------------
1 | """
2 | This module implements utility classes for formatting/printing agent messages.
3 | """
4 | 
5 | from ._rich_console import RichConsole
6 | 
7 | __all__ = ["RichConsole"]
8 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/test_filesurfer_agent.html:
--------------------------------------------------------------------------------
1 | <html>
2 |   <head>
3 |     <title>FileSurfer test file</title>
4 |   </head>
5 |   <body>
6 |     <h1>FileSurfer test H1</h1>
7 |     <p>FileSurfer test body</p>
8 |   </body>
9 | </html>


--------------------------------------------------------------------------------
/python/packages/autogen-ext/tests/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/python/packages/autogen-ext/tests/__init__.py


--------------------------------------------------------------------------------
/python/packages/autogen-ext/tests/conftest.py:
--------------------------------------------------------------------------------
 1 | import pytest
 2 | 
 3 | 
 4 | def pytest_addoption(parser: pytest.Parser) -> None:
 5 |     parser.addoption("--windows", action="store_true", default=False, help="Run tests for Windows")
 6 | 
 7 | 
 8 | def pytest_configure(config: pytest.Config) -> None:
 9 |     config.addinivalue_line("markers", "windows: mark test as requiring Windows")
10 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/tests/protos/serialization_test_pb2_grpc.pyi:
--------------------------------------------------------------------------------
 1 | """
 2 | @generated by mypy-protobuf.  Do not edit manually!
 3 | isort:skip_file
 4 | """
 5 | 
 6 | import abc
 7 | import collections.abc
 8 | import grpc
 9 | import grpc.aio
10 | import typing
11 | 
12 | _T = typing.TypeVar("_T")
13 | 
14 | class _MaybeAsyncIterator(collections.abc.AsyncIterator[_T], collections.abc.Iterator[_T], metaclass=abc.ABCMeta): ...
15 | 
16 | class _ServicerContext(grpc.ServicerContext, grpc.aio.ServicerContext):  # type: ignore[misc, type-arg]
17 |     ...
18 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/tests/task_centric_memory/data_files/insights/add_topic.yaml:
--------------------------------------------------------------------------------
1 | # Advice created manually for solving the autogen_package task.
2 | 
3 | insight: 'When somebody builds something on autogen and wants to contribute it to autogen,
4 |   instead of creating a new autogen package, it''s better for them to implement it in a separate github repo,
5 |   then just add the autogen-extension topic to that repo.
6 |   That way their contribution will be automatically discoverable through autogen''s page on community extensions:  https://microsoft.github.io/autogen/dev/user-guide/extensions-user-guide/index.html'
7 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/tests/task_centric_memory/data_files/insights/liar_advice.yaml:
--------------------------------------------------------------------------------
1 | # Advice created automatically for solving the 10_liars task.
2 | 
3 | insight: 'When solving logic puzzles, carefully consider all possible scenarios,
4 |   including the simplest ones, and remember that if everyone is lying,
5 |   their statements should naturally align with the known conditions without needing a truth-teller.
6 |   Always double-check that your conclusions don''t inadvertently introduce contradictions.'
7 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/tests/task_centric_memory/data_files/tasks/10_liars.yaml:
--------------------------------------------------------------------------------
1 | # Similar to the 100 vampires task, for testing generalization from one to the other.
2 | 
3 | task_description: 'You ask ten people ''How many of you are liars?''
4 |   They all answer ''At least one of us is not a liar.''
5 |   You happen to know that at least one of them IS a liar.
6 |   How many of them are liars in total?'
7 | 
8 | expected_answer: All of them are liars.
9 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/tests/task_centric_memory/data_files/tasks/autogen_package.yaml:
--------------------------------------------------------------------------------
1 | # Test where human advice is needed.
2 | 
3 | task_description: As a contribution to autogen, can I create a new autogen package for a copilot extension agent that I built on autogen?
4 | 
5 | expected_answer: It's best to have your agent in its own repo, then add the autogen-extension topic to that repo.
6 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/tests/task_centric_memory/data_files/tasks/cell_towers_1.yaml:
--------------------------------------------------------------------------------
 1 | # File-free version of a GAIA L1 task.
 2 | 
 3 | task_description: You are a telecommunications engineer who wants to build cell phone towers on a stretch of road.
 4 |                   Houses are located at mile markers 16, 17, 19, 11, 9, 10, 2, 5, 4.
 5 |                   Each cell phone tower can cover houses located next to the road within a 4-mile radius.
 6 |                   Find the minimum number of cell phone towers needed to cover all houses next to the road.
 7 |                   Your answer should be a positive numerical integer value.
 8 | 
 9 | expected_answer: '2'
10 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/tests/task_centric_memory/data_files/tasks/cell_towers_2.yaml:
--------------------------------------------------------------------------------
 1 | # Similar to the cell_towers_1 task.
 2 | 
 3 | task_description: You are a telecommunications engineer who wants to build cell phone towers on a stretch of road.
 4 |                   Houses are located at mile markers 17, 20, 19, 10, 11, 12, 3, 6.
 5 |                   Each cell phone tower can cover houses located next to the road within a 4-mile radius.
 6 |                   Find the minimum number of cell phone towers needed to cover all houses next to the road.
 7 |                   Your answer should be a positive numerical integer value.
 8 | 
 9 | expected_answer: '2'
10 | 


--------------------------------------------------------------------------------
/python/packages/autogen-ext/tests/tools/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/python/packages/autogen-ext/tests/tools/__init__.py


--------------------------------------------------------------------------------
/python/packages/autogen-ext/tests/tools/graphrag/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/python/packages/autogen-ext/tests/tools/graphrag/__init__.py


--------------------------------------------------------------------------------
/python/packages/autogen-ext/tests/tools/http/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/python/packages/autogen-ext/tests/tools/http/__init__.py


--------------------------------------------------------------------------------
/python/packages/autogen-studio/.gitignore:
--------------------------------------------------------------------------------
 1 | database.sqlite
 2 | .cache/*
 3 | autogenstudio/web/files/user/*
 4 | autogenstudio/test
 5 | autogenstudio/database/alembic.ini 
 6 | autogenstudio/database/alembic/*
 7 | autogenstudio/web/files/ui/*
 8 | OAI_CONFIG_LIST
 9 | scratch/
10 | autogenstudio/web/workdir/*
11 | autogenstudio/web/ui/*
12 | autogenstudio/web/skills/user/*
13 | .release.sh
14 | .nightly.sh
15 | notebooks/test
16 | 
17 | notebooks/work_dir/*
18 | notebooks/test.db
19 | 
20 | # Byte-compiled / optimized / DLL files
21 | __pycache__/
22 | *.py[cod]
23 | *$py.class
24 | 
25 | # Environments
26 | .env
27 | .venv
28 | env/
29 | venv/
30 | ENV/
31 | env.bak/
32 | venv.bak/
33 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/Dockerfile:
--------------------------------------------------------------------------------
 1 | FROM python:3.10-slim
 2 | WORKDIR /code
 3 | 
 4 | RUN pip install -U gunicorn autogenstudio
 5 | 
 6 | # Create a non-root user
 7 | RUN useradd -m -u 1000 user
 8 | USER user
 9 | ENV HOME=/home/user \
10 |     PATH=/home/user/.local/bin:$PATH \
11 |     AUTOGENSTUDIO_APPDIR=/home/user/app
12 | 
13 | WORKDIR $HOME/app
14 | 
15 | COPY --chown=user . $HOME/app
16 | 
17 | CMD gunicorn -w $((2 * $(getconf _NPROCESSORS_ONLN) + 1)) --timeout 12600 -k uvicorn.workers.UvicornWorker autogenstudio.web.app:app --bind "0.0.0.0:8081"
18 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/MANIFEST.in:
--------------------------------------------------------------------------------
1 | recursive-include  autogenstudio/web/ui *
2 | recursive-include  autogenstudio/web/database.sqlite
3 | recursive-exclude  notebooks *
4 | 
5 | recursive-exclude  frontend *
6 | recursive-exclude  docs *
7 | recursive-exclude  tests *
8 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/autogenstudio/__init__.py:
--------------------------------------------------------------------------------
1 | from .database.db_manager import DatabaseManager
2 | from .datamodel import Team
3 | from .teammanager import TeamManager
4 | from .version import __version__
5 | 
6 | __all__ = ["DatabaseManager", "Team", "TeamManager", "__version__"]
7 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/autogenstudio/database/__init__.py:
--------------------------------------------------------------------------------
1 | from .db_manager import DatabaseManager
2 | 
3 | __all__ = [
4 |     "DatabaseManager",
5 | ]
6 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/autogenstudio/eval/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/python/packages/autogen-studio/autogenstudio/eval/__init__.py


--------------------------------------------------------------------------------
/python/packages/autogen-studio/autogenstudio/gallery/__init__.py:
--------------------------------------------------------------------------------
1 | from .builder import GalleryBuilder, create_default_gallery
2 | 
3 | __all__ = ["GalleryBuilder", "create_default_gallery"]
4 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/autogenstudio/gallery/tools/__init__.py:
--------------------------------------------------------------------------------
 1 | from .bing_search import bing_search_tool
 2 | from .calculator import calculator_tool
 3 | from .fetch_webpage import fetch_webpage_tool
 4 | from .generate_image import generate_image_tool
 5 | from .google_search import google_search_tool
 6 | 
 7 | __all__ = [
 8 |     "bing_search_tool",
 9 |     "calculator_tool",
10 |     "google_search_tool",
11 |     "generate_image_tool",
12 |     "fetch_webpage_tool",
13 | ]
14 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/autogenstudio/lite/__init__.py:
--------------------------------------------------------------------------------
1 | from .studio import LiteStudio
2 | 
3 | __all__ = ["LiteStudio"]
4 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/autogenstudio/teammanager/__init__.py:
--------------------------------------------------------------------------------
1 | from .teammanager import TeamManager
2 | 
3 | __all__ = ["TeamManager"]
4 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/autogenstudio/utils/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/python/packages/autogen-studio/autogenstudio/utils/__init__.py


--------------------------------------------------------------------------------
/python/packages/autogen-studio/autogenstudio/validation/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/python/packages/autogen-studio/autogenstudio/validation/__init__.py


--------------------------------------------------------------------------------
/python/packages/autogen-studio/autogenstudio/version.py:
--------------------------------------------------------------------------------
1 | VERSION = "0.4.3"
2 | __version__ = VERSION
3 | APP_NAME = "autogenstudio"
4 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/autogenstudio/web/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/python/packages/autogen-studio/autogenstudio/web/__init__.py


--------------------------------------------------------------------------------
/python/packages/autogen-studio/autogenstudio/web/auth/__init__.py:
--------------------------------------------------------------------------------
 1 | from .authroutes import router
 2 | from .dependencies import get_current_user, require_admin, require_authenticated, require_roles
 3 | from .exceptions import AuthException
 4 | from .manager import AuthManager
 5 | from .middleware import AuthMiddleware
 6 | from .models import AuthConfig, User
 7 | from .wsauth import WebSocketAuthHandler
 8 | 
 9 | __all__ = [
10 |     "AuthManager",
11 |     "AuthMiddleware",
12 |     "AuthConfig",
13 |     "User",
14 |     "AuthException",
15 |     "router",
16 |     "get_current_user",
17 |     "require_authenticated",
18 |     "require_roles",
19 |     "require_admin",
20 |     "WebSocketAuthHandler",
21 | ]
22 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/autogenstudio/web/config.py:
--------------------------------------------------------------------------------
 1 | # api/config.py
 2 | 
 3 | from pydantic_settings import BaseSettings
 4 | 
 5 | 
 6 | class Settings(BaseSettings):
 7 |     DATABASE_URI: str = "sqlite:///./autogen04203.db"
 8 |     API_DOCS: bool = False
 9 |     CLEANUP_INTERVAL: int = 300  # 5 minutes
10 |     SESSION_TIMEOUT: int = 3600  # 1 hour
11 |     CONFIG_DIR: str = "configs"  # Default config directory relative to app_root
12 |     DEFAULT_USER_ID: str = "guestuser@gmail.com"
13 |     UPGRADE_DATABASE: bool = False
14 | 
15 |     # Lite mode settings
16 |     LITE_MODE: bool = False
17 |     LITE_TEAM_FILE: str = ""
18 |     LITE_SESSION_NAME: str = ""
19 | 
20 |     model_config = {"env_prefix": "AUTOGENSTUDIO_"}
21 | 
22 | 
23 | settings = Settings()
24 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/autogenstudio/web/managers/__init__.py:
--------------------------------------------------------------------------------
1 | # from .connection import WebSocketManager
2 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/autogenstudio/web/routes/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/python/packages/autogen-studio/autogenstudio/web/routes/__init__.py


--------------------------------------------------------------------------------
/python/packages/autogen-studio/docs/ags_screen.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:876389d20f68c9c6e230563a145f8e10c6870bf8633163f0a6fe1f5db8d8ffe8
3 | size 195570
4 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/frontend/.env.default:
--------------------------------------------------------------------------------
1 | GATSBY_API_URL=http://127.0.0.1:8081/api 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/frontend/.gitignore:
--------------------------------------------------------------------------------
1 | node_modules/
2 | .cache/
3 | public
4 | src/gatsby-types.d.ts
5 | .env.development
6 | .env.production


--------------------------------------------------------------------------------
/python/packages/autogen-studio/frontend/gatsby-browser.js:
--------------------------------------------------------------------------------
1 | import "antd/dist/reset.css";
2 | import "./src/styles/global.css";
3 | 
4 | import AuthProvider from "./src/hooks/provider";
5 | 
6 | export const wrapRootElement = AuthProvider;
7 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/frontend/gatsby-ssr.tsx:
--------------------------------------------------------------------------------
 1 | import React from "react";
 2 | 
 3 | const codeToRunOnClient = `(function() {
 4 |   try {
 5 |     var mode = localStorage.getItem('darkmode');
 6 |     document.getElementsByTagName("html")[0].className === 'dark' ? 'dark' : 'light';
 7 |   } catch (e) {}
 8 | })();`;
 9 | 
10 | export const onRenderBody = ({ setHeadComponents }) =>
11 |   setHeadComponents([
12 |     <script
13 |       key="myscript"
14 |       dangerouslySetInnerHTML={{ __html: codeToRunOnClient }}
15 |     />,
16 |   ]);
17 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/frontend/postcss.config.js:
--------------------------------------------------------------------------------
1 | module.exports = {
2 |   plugins: {
3 |     tailwindcss: {},
4 |     autoprefixer: {},
5 |   },
6 | }
7 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/frontend/src/components/shared/index.ts:
--------------------------------------------------------------------------------
1 | export { AddComponentDropdown } from "./AddComponentDropdown";
2 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/frontend/src/components/types/app.ts:
--------------------------------------------------------------------------------
1 | export interface IStatus {
2 |   message: string;
3 |   status: boolean;
4 |   data?: any;
5 | }
6 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/frontend/src/components/utils/baseapi.ts:
--------------------------------------------------------------------------------
 1 | import { getServerUrl } from "./utils";
 2 | 
 3 | // baseApi.ts
 4 | export abstract class BaseAPI {
 5 |   protected getBaseUrl(): string {
 6 |     return getServerUrl();
 7 |   }
 8 | 
 9 |   protected getHeaders(): HeadersInit {
10 |     // Get auth token from localStorage
11 |     const token = localStorage.getItem("auth_token");
12 | 
13 |     const headers: HeadersInit = {
14 |       "Content-Type": "application/json",
15 |     };
16 | 
17 |     // Add authorization header if token exists
18 |     if (token) {
19 |       headers["Authorization"] = `Bearer ${token}`;
20 |     }
21 | 
22 |     return headers;
23 |   }
24 | 
25 |   // Other common methods
26 | }
27 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/frontend/src/components/views/deploy/types.tsx:
--------------------------------------------------------------------------------
 1 | export interface Guide {
 2 |   id: string;
 3 |   title: string;
 4 |   type: "python" | "docker" | "cloud";
 5 | }
 6 | 
 7 | export const defaultGuides: Guide[] = [
 8 |   {
 9 |     id: "python-setup",
10 |     title: "Python",
11 |     type: "python",
12 |   },
13 |   {
14 |     id: "docker-setup",
15 |     title: "Docker",
16 |     type: "docker",
17 |   },
18 |   // {
19 |   //   id: "cloud-deploy",
20 |   //   title: "Cloud",
21 |   //   type: "cloud",
22 |   // },
23 | ];
24 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/frontend/src/components/views/gallery/types.ts:
--------------------------------------------------------------------------------
 1 | import { Gallery } from "../../types/datamodel";
 2 | 
 3 | // export interface GalleryAPI {
 4 | //   listGalleries: () => Promise<Gallery[]>;
 5 | //   getGallery: (id: string) => Promise<Gallery>;
 6 | //   createGallery: (gallery: Gallery) => Promise<Gallery>;
 7 | //   updateGallery: (gallery: Gallery) => Promise<Gallery>;
 8 | //   deleteGallery: (id: string) => Promise<void>;
 9 | // }
10 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/frontend/src/components/views/gallery/utils.ts:
--------------------------------------------------------------------------------
 1 | import { GalleryConfig } from "../../types/datamodel";
 2 | 
 3 | // Load and parse the gallery JSON file
 4 | const loadGalleryFromJson = (): GalleryConfig => {
 5 |   try {
 6 |     // You can adjust the path to your JSON file as needed
 7 |     const galleryJson = require("./default_gallery.json");
 8 |     return galleryJson as GalleryConfig;
 9 |   } catch (error) {
10 |     console.error("Error loading gallery JSON:", error);
11 |     throw error;
12 |   }
13 | };
14 | 
15 | export const defaultGallery: GalleryConfig = loadGalleryFromJson();
16 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/frontend/src/components/views/labs/types.tsx:
--------------------------------------------------------------------------------
 1 | export interface Lab {
 2 |   id: string;
 3 |   title: string;
 4 |   type: "python" | "docker" | "cloud";
 5 | }
 6 | 
 7 | export const defaultLabs: Lab[] = [
 8 |   // {
 9 |   //   id: "component-builder",
10 |   //   title: "Component Builder",
11 |   //   type: "python",
12 |   // },
13 |   {
14 |     id: "tool-maker",
15 |     title: "Tool Maker",
16 |     type: "python",
17 |   },
18 | ];
19 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/frontend/src/components/views/markdown.tsx:
--------------------------------------------------------------------------------
 1 | import React, { ReactNode } from "react";
 2 | import Markdown from "react-markdown";
 3 | 
 4 | interface MarkdownViewProps {
 5 |   content: string;
 6 |   className?: string;
 7 | }
 8 | 
 9 | export const MarkdownView: React.FC<MarkdownViewProps> = ({
10 |   content,
11 |   className = "",
12 | }) => {
13 |   return (
14 |     <div className={`text-sm w-full text-primary rounded   ${className}`}>
15 |       <Markdown>{content}</Markdown>
16 |     </div>
17 |   );
18 | };
19 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/frontend/src/components/views/mcp/index.ts:
--------------------------------------------------------------------------------
 1 | export { default as McpManager } from "./manager";
 2 | export { default as McpSidebar } from "./sidebar";
 3 | export { default as McpDetail } from "./detail";
 4 | export {
 5 |   mcpAPI,
 6 |   Tool,
 7 |   CallToolResult,
 8 |   ListToolsResponse,
 9 |   CallToolResponse,
10 | } from "./api";
11 | 
12 | export { default } from "./manager";
13 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/frontend/src/components/views/mcp/types.ts:
--------------------------------------------------------------------------------
 1 | import type { McpServerParams } from "../../types/datamodel";
 2 | 
 3 | // Define a more complete MCP Server interface for the playground
 4 | export interface McpServer {
 5 |   id: string;
 6 |   name: string;
 7 |   description?: string;
 8 |   serverParams: McpServerParams;
 9 |   isConnected?: boolean;
10 |   lastConnected?: string;
11 |   tools?: Array<{
12 |     name: string;
13 |     description: string;
14 |     schema?: any;
15 |   }>;
16 | }
17 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/frontend/src/components/views/playground/types.ts:
--------------------------------------------------------------------------------
 1 | import type { Session, Team } from "../../types/datamodel";
 2 | 
 3 | export interface SessionEditorProps {
 4 |   session?: Session;
 5 |   onSave: (session: Partial<Session>) => Promise<void>;
 6 |   onCancel: () => void;
 7 |   isOpen: boolean;
 8 |   teams: Team[];
 9 | }
10 | 
11 | export interface SessionListProps {
12 |   sessions: Session[];
13 |   currentSession?: Session | null;
14 |   onSelect: (session: Session) => void;
15 |   onEdit: (session: Session) => void;
16 |   onDelete: (sessionId: number) => void;
17 |   isLoading?: boolean;
18 | }
19 | 
20 | export interface SessionFormState {
21 |   name: string;
22 |   team_id: string;
23 |   isSubmitting: boolean;
24 |   error?: string;
25 | }
26 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/frontend/src/components/views/settings/types.tsx:
--------------------------------------------------------------------------------
1 | import { LucideIcon } from "lucide-react";
2 | 
3 | export interface SettingsSection {
4 |   id: string;
5 |   title: string;
6 |   icon: LucideIcon;
7 |   content: () => JSX.Element;
8 | }
9 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/frontend/src/components/views/teambuilder/builder/builder.css:
--------------------------------------------------------------------------------
 1 | .drop-target-valid {
 2 |   outline: 2px solid #4caf50;
 3 |   outline-offset: 4px;
 4 |   transition: outline-color 0.2s;
 5 | }
 6 | 
 7 | .drop-target-invalid {
 8 |   outline: 2px dashed #f44336;
 9 |   outline-offset: 4px;
10 | }
11 | 
12 | .droppable-zone {
13 |   min-height: 40px;
14 |   border: 2px dashed #ccc;
15 |   border-radius: 4px;
16 |   margin: 8px 0;
17 | }
18 | 
19 | .droppable-zone.can-drop {
20 |   border-color: #4caf50;
21 |   background: rgba(76, 175, 80, 0.1);
22 | }
23 | 
24 | .my-left-handle {
25 |   @apply bg-accent w-1 h-3 rounded-r-sm -ml-1 border-0 !important;
26 | }
27 | 
28 | .my-right-handle {
29 |   @apply bg-accent w-1 h-3  rounded-l-sm -mr-1 border-0 !important;
30 | }
31 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/frontend/src/components/views/teambuilder/builder/component-editor/fields/workbench/index.ts:
--------------------------------------------------------------------------------
1 | export { WorkbenchFields } from "./workbench-fields";
2 | export { McpCapabilitiesPanel } from "./mcp-capabilities-panel";
3 | export { McpToolsTab } from "./mcp-tools-tab";
4 | export { McpResourcesTab } from "./mcp-resources-tab";
5 | export { McpPromptsTab } from "./mcp-prompts-tab";
6 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/frontend/src/components/views/teambuilder/types.ts:
--------------------------------------------------------------------------------
 1 | import type { Component, Team, TeamConfig } from "../../types/datamodel";
 2 | 
 3 | export interface TeamEditorProps {
 4 |   team?: Team;
 5 |   onSave: (team: Partial<Team>) => Promise<void>;
 6 |   onCancel: () => void;
 7 |   isOpen: boolean;
 8 | }
 9 | 
10 | export interface TeamListProps {
11 |   teams: Team[];
12 |   currentTeam?: Team | null;
13 |   onSelect: (team: Team) => void;
14 |   onEdit: (team: Team) => void;
15 |   onDelete: (teamId: number) => void;
16 |   isLoading?: boolean;
17 | }
18 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/frontend/src/images/icon.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:7ec19e710d8b38d99b5f1b170db18eb192cd3a50fe80f1c103f88cce68e057b4
3 | size 33034
4 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/frontend/src/index.d.ts:
--------------------------------------------------------------------------------
1 | declare module "*.jpg";
2 | declare module "*.png";
3 | declare module "*.svg";
4 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/frontend/src/pages/build.tsx:
--------------------------------------------------------------------------------
 1 | import * as React from "react";
 2 | import Layout from "../components/layout";
 3 | import { graphql } from "gatsby";
 4 | import TeamManager from "../components/views/teambuilder/manager";
 5 | 
 6 | // markup
 7 | const IndexPage = ({ data }: any) => {
 8 |   return (
 9 |     <Layout meta={data.site.siteMetadata} title="Home" link={"/build"}>
10 |       <main style={{ height: "100%" }} className=" h-full ">
11 |         <TeamManager />
12 |       </main>
13 |     </Layout>
14 |   );
15 | };
16 | 
17 | export const query = graphql`
18 |   query HomePageQuery {
19 |     site {
20 |       siteMetadata {
21 |         description
22 |         title
23 |       }
24 |     }
25 |   }
26 | `;
27 | 
28 | export default IndexPage;
29 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/frontend/src/pages/deploy.tsx:
--------------------------------------------------------------------------------
 1 | import * as React from "react";
 2 | import Layout from "../components/layout";
 3 | import { graphql } from "gatsby";
 4 | import DeployManager from "../components/views/deploy/manager";
 5 | 
 6 | // markup
 7 | const DeployPage = ({ data }: any) => {
 8 |   return (
 9 |     <Layout meta={data.site.siteMetadata} title="Home" link={"/deploy"}>
10 |       <main style={{ height: "100%" }} className=" h-full ">
11 |         <DeployManager />
12 |       </main>
13 |     </Layout>
14 |   );
15 | };
16 | 
17 | export const query = graphql`
18 |   query HomePageQuery {
19 |     site {
20 |       siteMetadata {
21 |         description
22 |         title
23 |       }
24 |     }
25 |   }
26 | `;
27 | 
28 | export default DeployPage;
29 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/frontend/src/pages/gallery.tsx:
--------------------------------------------------------------------------------
 1 | import * as React from "react";
 2 | import Layout from "../components/layout";
 3 | import { graphql } from "gatsby";
 4 | import GalleryManager from "../components/views/gallery/manager";
 5 | 
 6 | // markup
 7 | const GalleryPage = ({ data }: any) => {
 8 |   return (
 9 |     <Layout meta={data.site.siteMetadata} title="Home" link={"/gallery"}>
10 |       <main style={{ height: "100%" }} className=" h-full ">
11 |         <GalleryManager />
12 |       </main>
13 |     </Layout>
14 |   );
15 | };
16 | 
17 | export const query = graphql`
18 |   query HomePageQuery {
19 |     site {
20 |       siteMetadata {
21 |         description
22 |         title
23 |       }
24 |     }
25 |   }
26 | `;
27 | 
28 | export default GalleryPage;
29 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/frontend/src/pages/mcp.tsx:
--------------------------------------------------------------------------------
 1 | import * as React from "react";
 2 | import Layout from "../components/layout";
 3 | import { graphql } from "gatsby";
 4 | import McpManager from "../components/views/mcp/manager";
 5 | 
 6 | // markup
 7 | const McpPage = ({ data }: any) => {
 8 |   return (
 9 |     <Layout meta={data.site.siteMetadata} title="MCP Playground" link={"/mcp"}>
10 |       <main style={{ height: "100%" }} className="h-full">
11 |         <McpManager />
12 |       </main>
13 |     </Layout>
14 |   );
15 | };
16 | 
17 | export const query = graphql`
18 |   query McpPageQuery {
19 |     site {
20 |       siteMetadata {
21 |         description
22 |         title
23 |       }
24 |     }
25 |   }
26 | `;
27 | 
28 | export default McpPage;
29 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/frontend/src/pages/settings.tsx:
--------------------------------------------------------------------------------
 1 | import * as React from "react";
 2 | import Layout from "../components/layout";
 3 | import { graphql } from "gatsby";
 4 | import { SettingsManager } from "../components/views/settings/manager";
 5 | 
 6 | // markup
 7 | const SettingsPage = ({ data }: any) => {
 8 |   return (
 9 |     <Layout meta={data.site.siteMetadata} title="Home" link={"/settings"}>
10 |       <main style={{ height: "100%" }} className=" h-full ">
11 |         <SettingsManager />
12 |       </main>
13 |     </Layout>
14 |   );
15 | };
16 | 
17 | export const query = graphql`
18 |   query HomePageQuery {
19 |     site {
20 |       siteMetadata {
21 |         description
22 |         title
23 |       }
24 |     }
25 |   }
26 | `;
27 | 
28 | export default SettingsPage;
29 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/requirements.txt:
--------------------------------------------------------------------------------
1 | .
2 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/setup.py:
--------------------------------------------------------------------------------
1 | from setuptools import setup
2 | 
3 | setup()
4 | 


--------------------------------------------------------------------------------
/python/packages/autogen-studio/tests/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/python/packages/autogen-studio/tests/__init__.py


--------------------------------------------------------------------------------
/python/packages/autogen-studio/tests/test_datamodel_types.py:
--------------------------------------------------------------------------------
 1 | import pytest
 2 | 
 3 | from autogenstudio.datamodel.types import LLMCallEventMessage
 4 | 
 5 | def test_LLMCallEventMessage_inner_funcs():
 6 |     """Test the inner functions of LLMCallEventMessage"""
 7 |     # Create a mock LLMCallEventMessage
 8 |     message = LLMCallEventMessage(
 9 |         content="Test message"
10 |     )
11 | 
12 |     # Test the inner functions
13 |     assert message.to_text() == "Test message"
14 |     assert message.to_model_text() == "Test message"
15 |     with pytest.raises(NotImplementedError, match="This message type is not supported."):
16 |         message.to_model_message()


--------------------------------------------------------------------------------
/python/packages/autogen-test-utils/README.md:
--------------------------------------------------------------------------------
1 | # test-utils
2 | 


--------------------------------------------------------------------------------
/python/packages/autogen-test-utils/pyproject.toml:
--------------------------------------------------------------------------------
 1 | [build-system]
 2 | build-backend="hatchling.build"
 3 | requires     =[ "hatchling" ]
 4 | 
 5 | [project]
 6 | dependencies   =[ "autogen-core", "opentelemetry-sdk>=1.27.0", "pytest" ]
 7 | license        ={ file="LICENSE-CODE" }
 8 | name           ="autogen-test-utils"
 9 | requires-python=">=3.10"
10 | version        ="0.0.0"
11 | 
12 | [tool.ruff]
13 | extend ="../../pyproject.toml"
14 | include=[ "src/**" ]
15 | 
16 | [tool.pyright]
17 | extends="../../pyproject.toml"
18 | include=[ "src" ]
19 | 
20 | [tool.poe]
21 | include="../../shared_tasks.toml"
22 | 
23 | [tool.poe.tasks]
24 | mypy="mypy --config-file $POE_ROOT/../../pyproject.toml src"
25 | test="python -c \"import sys; sys.exit(0)\""
26 | 


--------------------------------------------------------------------------------
/python/packages/autogen-test-utils/src/autogen_test_utils/py.typed:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/python/packages/autogen-test-utils/src/autogen_test_utils/py.typed


--------------------------------------------------------------------------------
/python/packages/autogen-test-utils/tests/test.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/python/packages/autogen-test-utils/tests/test.py


--------------------------------------------------------------------------------
/python/packages/component-schema-gen/README.md:
--------------------------------------------------------------------------------
1 | # component-schema-gen
2 | 
3 | This is a tool to generate schema for built in components.
4 | 
5 | Simply run `gen-component-schema` and it will print the schema to be used.
6 | 


--------------------------------------------------------------------------------
/python/packages/component-schema-gen/src/component_schema_gen/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/python/packages/component-schema-gen/src/component_schema_gen/__init__.py


--------------------------------------------------------------------------------
/python/packages/component-schema-gen/src/component_schema_gen/py.typed:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/python/packages/component-schema-gen/src/component_schema_gen/py.typed


--------------------------------------------------------------------------------
/python/packages/magentic-one-cli/README.md:
--------------------------------------------------------------------------------
1 | # magentic-one-cli
2 | 


--------------------------------------------------------------------------------
/python/packages/magentic-one-cli/src/magentic_one_cli/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/python/packages/magentic-one-cli/src/magentic_one_cli/__init__.py


--------------------------------------------------------------------------------
/python/packages/magentic-one-cli/src/magentic_one_cli/__main__.py:
--------------------------------------------------------------------------------
1 | from ._m1 import main
2 | 
3 | main()
4 | 


--------------------------------------------------------------------------------
/python/packages/magentic-one-cli/src/magentic_one_cli/py.typed:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/python/packages/magentic-one-cli/src/magentic_one_cli/py.typed


--------------------------------------------------------------------------------
/python/packages/pyautogen/pyproject.toml:
--------------------------------------------------------------------------------
 1 | [build-system]
 2 | requires = ["hatchling"]
 3 | build-backend = "hatchling.build"
 4 | 
 5 | [project]
 6 | name = "pyautogen"
 7 | version = "0.10.0"
 8 | license = {file = "LICENSE-CODE"}
 9 | description = "A programming framework for agentic AI. Proxy package for autogen-agentchat."
10 | readme = "README.md"
11 | requires-python = ">=3.10"
12 | classifiers = [
13 |     "Programming Language :: Python :: 3",
14 |     "License :: OSI Approved :: MIT License",
15 |     "Operating System :: OS Independent",
16 | ]
17 | dependencies = [
18 |     "autogen-agentchat>=0.6.4",
19 | ]
20 | 
21 | [tool.hatch.build.targets.wheel]
22 | packages = ["src/pyautogen"]
23 | 
24 | [tool.hatch.build.targets.sdist]
25 | include = ["pyproject.toml", "README.md", "LICENSE-CODE", "src/**"]


--------------------------------------------------------------------------------
/python/packages/pyautogen/src/pyautogen/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/python/packages/pyautogen/src/pyautogen/__init__.py


--------------------------------------------------------------------------------
/python/samples/agentchat_azure_postgresql/README.md:
--------------------------------------------------------------------------------
 1 | # **Multi-Agent PostgreSQL Data Management System with AutoGen and Azure PostgreSQL**
 2 | 
 3 | 
 4 | <div align="center">
 5 |   <img src="https://github.com/mehrsa/MultiAgent_Azure_PostgreSQL_AutoGen0.4/blob/main/misc/Drawing%203.png" alt="Architecture">
 6 | </div>
 7 | 
 8 | Go to below repository to try out a demo demonstrating how to build a **multi-agent AI system** for managing shipment data stored on an Azure PostgreSQL database:
 9 | 
10 | [MultiAgent_Azure_PostgreSQL_AutoGen](https://github.com/Azure-Samples/MultiAgent_Azure_PostgreSQL_AutoGen0.4/tree/main)
11 | 
12 | 
13 | 


--------------------------------------------------------------------------------
/python/samples/agentchat_chainlit/model_config.yaml:
--------------------------------------------------------------------------------
1 | # Use Open AI with key
2 | provider: autogen_ext.models.openai.OpenAIChatCompletionClient
3 | config:
4 |   model: gpt-4o
5 |   api_key: REPLACE_WITH_YOUR_API_KEY
6 | 


--------------------------------------------------------------------------------
/python/samples/agentchat_chess_game/.gitignore:
--------------------------------------------------------------------------------
1 | model_config.yml
2 | model_config.yaml


--------------------------------------------------------------------------------
/python/samples/agentchat_fastapi/.gitignore:
--------------------------------------------------------------------------------
1 | model_config.yaml
2 | agent_state.json
3 | agent_history.json
4 | team_state.json
5 | team_history.json
6 | 


--------------------------------------------------------------------------------
/python/samples/agentchat_graphrag/.gitignore:
--------------------------------------------------------------------------------
1 | model_config.yaml
2 | data
3 | cache


--------------------------------------------------------------------------------
/python/samples/agentchat_graphrag/requirements.txt:
--------------------------------------------------------------------------------
1 | autogen-agentchat
2 | autogen-ext
3 | pyyaml


--------------------------------------------------------------------------------
/python/samples/agentchat_streamlit/.gitignore:
--------------------------------------------------------------------------------
1 | model_config.yml


--------------------------------------------------------------------------------
/python/samples/core_async_human_in_the_loop/.gitignore:
--------------------------------------------------------------------------------
1 | model_config.yml
2 | 


--------------------------------------------------------------------------------
/python/samples/core_async_human_in_the_loop/README.md:
--------------------------------------------------------------------------------
 1 | # Async Human-in-the-Loop Example
 2 | 
 3 | An example showing human-in-the-loop which waits for human input before making the tool call.
 4 | 
 5 | ## Prerequisites
 6 | 
 7 | First, you need a shell with AutoGen core and required dependencies installed.
 8 | 
 9 | ```bash
10 | pip install "autogen-ext[openai,azure]" "pyyaml"
11 | ```
12 | 
13 | ## Model Configuration
14 | 
15 | The model configuration should defined in a `model_config.yml` file.
16 | Use `model_config_template.yml` as a template.
17 | 
18 | ## Running the example
19 | 
20 | ```bash
21 | python main.py
22 | ```
23 | 


--------------------------------------------------------------------------------
/python/samples/core_chainlit/.gitignore:
--------------------------------------------------------------------------------
1 | model_config.yaml
2 | .chainlit
3 | chainlit.md


--------------------------------------------------------------------------------
/python/samples/core_chess_game/.gitignore:
--------------------------------------------------------------------------------
1 | model_config.yml
2 | 


--------------------------------------------------------------------------------
/python/samples/core_chess_game/README.md:
--------------------------------------------------------------------------------
 1 | # Chess Game Example
 2 | 
 3 | An example with two chess player agents that executes its own tools to demonstrate tool use and reflection on tool use.
 4 | 
 5 | ## Prerequisites
 6 | 
 7 | First, you need a shell with AutoGen core and required dependencies installed.
 8 | 
 9 | ```bash
10 | pip install "autogen-ext[openai,azure]" "chess" "pyyaml"
11 | ```
12 | 
13 | ## Model Configuration
14 | 
15 | The model configuration should defined in a `model_config.yml` file.
16 | Use `model_config_template.yml` as a template.
17 | 
18 | ## Running the example
19 | 
20 | ```bash
21 | python main.py
22 | ```
23 | 


--------------------------------------------------------------------------------
/python/samples/core_distributed-group-chat/.gitignore:
--------------------------------------------------------------------------------
1 | .chainlit
2 | chainlit.md


--------------------------------------------------------------------------------
/python/samples/core_distributed-group-chat/public/avatars/editor.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:ca081360cdb35adbc43e282675757a8f94a6b59cba38224c36a6ca2a80a4dce5
3 | size 5675
4 | 


--------------------------------------------------------------------------------
/python/samples/core_distributed-group-chat/public/avatars/group_chat_manager.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:7e8370f35865293d3126f7f282e6ffef8052a266d205ce2acbee5d211c531a18
3 | size 6026
4 | 


--------------------------------------------------------------------------------
/python/samples/core_distributed-group-chat/public/avatars/user.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:52e3e0154e49f6a09b2a16d6671acb98c32ab53490ff080f0674e83163c640e8
3 | size 5215
4 | 


--------------------------------------------------------------------------------
/python/samples/core_distributed-group-chat/public/avatars/writer.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:bd82203ec3fa337ea5b61de36c3e4223c175871e40e34ee6b36c3281130979b4
3 | size 5426
4 | 


--------------------------------------------------------------------------------
/python/samples/core_distributed-group-chat/public/favicon.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:a60b36ba9e366a244eb641ca59588b6734839c360a42405a369d7af77e7613fc
3 | size 3700
4 | 


--------------------------------------------------------------------------------
/python/samples/core_distributed-group-chat/public/logo.png:
--------------------------------------------------------------------------------
1 | version https://git-lfs.github.com/spec/v1
2 | oid sha256:a60b36ba9e366a244eb641ca59588b6734839c360a42405a369d7af77e7613fc
3 | size 3700
4 | 


--------------------------------------------------------------------------------
/python/samples/core_distributed-group-chat/run_host.py:
--------------------------------------------------------------------------------
 1 | import asyncio
 2 | 
 3 | from _types import HostConfig
 4 | from _utils import load_config
 5 | from autogen_ext.runtimes.grpc import GrpcWorkerAgentRuntimeHost
 6 | from rich.console import Console
 7 | from rich.markdown import Markdown
 8 | 
 9 | 
10 | async def main(host_config: HostConfig):
11 |     host = GrpcWorkerAgentRuntimeHost(address=host_config.address)
12 |     host.start()
13 | 
14 |     console = Console()
15 |     console.print(
16 |         Markdown(f"**`Distributed Host`** is now running and listening for connection at **`{host_config.address}`**")
17 |     )
18 |     await host.stop_when_signal()
19 | 
20 | 
21 | if __name__ == "__main__":
22 |     asyncio.run(main(load_config().host))
23 | 


--------------------------------------------------------------------------------
/python/samples/core_streaming_handoffs_fastapi/.gitignore:
--------------------------------------------------------------------------------
1 | model_config.yaml


--------------------------------------------------------------------------------
/python/samples/core_streaming_handoffs_fastapi/models.py:
--------------------------------------------------------------------------------
 1 | from typing import List
 2 | from autogen_core.models import LLMMessage
 3 | from pydantic import BaseModel
 4 | 
 5 | 
 6 | class UserLogin(BaseModel):
 7 |     pass
 8 | 
 9 | class UserTask(BaseModel):
10 |     context: List[LLMMessage]
11 | 
12 | class AgentResponse(BaseModel):
13 |     reply_to_topic_type: str
14 |     context: List[LLMMessage]
15 | 


--------------------------------------------------------------------------------
/python/samples/core_streaming_handoffs_fastapi/requirements.txt:
--------------------------------------------------------------------------------
1 | autogen-core>=0.5.4
2 | autogen-ext[openai,azure]>=0.5.4
3 | fastapi==0.115.12
4 | uvicorn==0.34.2
5 | PyYAML==6.0.2
6 | 


--------------------------------------------------------------------------------
/python/samples/core_streaming_handoffs_fastapi/topics.py:
--------------------------------------------------------------------------------
1 | sales_agent_topic_type = "SalesAgent"
2 | issues_and_repairs_agent_topic_type = "IssuesAndRepairsAgent"
3 | triage_agent_topic_type = "TriageAgent"
4 | user_topic_type = "User"
5 | 
6 | 


--------------------------------------------------------------------------------
/python/samples/core_streaming_response_fastapi/.gitignore:
--------------------------------------------------------------------------------
1 | model_config.yaml
2 | agent_state.json
3 | agent_history.json
4 | team_state.json
5 | team_history.json
6 | 


--------------------------------------------------------------------------------
/python/samples/core_xlang_hello_python_agent/protos/__init__.py:
--------------------------------------------------------------------------------
1 | """
2 | The :mod:`autogen_core.worker.protos` module provides Google Protobuf classes for agent-worker communication
3 | """
4 | 
5 | import os
6 | import sys
7 | 
8 | sys.path.insert(0, os.path.abspath(os.path.dirname(__file__)))
9 | 


--------------------------------------------------------------------------------
/python/samples/core_xlang_hello_python_agent/protos/agent_events_pb2_grpc.pyi:
--------------------------------------------------------------------------------
 1 | """
 2 | @generated by mypy-protobuf.  Do not edit manually!
 3 | isort:skip_file
 4 | """
 5 | 
 6 | import abc
 7 | import collections.abc
 8 | import grpc
 9 | import grpc.aio
10 | import typing
11 | 
12 | _T = typing.TypeVar("_T")
13 | 
14 | class _MaybeAsyncIterator(collections.abc.AsyncIterator[_T], collections.abc.Iterator[_T], metaclass=abc.ABCMeta): ...
15 | 
16 | class _ServicerContext(grpc.ServicerContext, grpc.aio.ServicerContext):  # type: ignore[misc, type-arg]
17 |     ...
18 | 


--------------------------------------------------------------------------------
/python/samples/gitty/.python-version:
--------------------------------------------------------------------------------
1 | 3.11
2 | 


--------------------------------------------------------------------------------
/python/samples/gitty/README.md:
--------------------------------------------------------------------------------
 1 | # gitty (Warning: WIP)
 2 | 
 3 | This is an AutoGen powered CLI that generates draft replies for issues and pull requests
 4 | to reduce maintenance overhead for open source projects.
 5 | 
 6 | Simple installation and CLI:
 7 | 
 8 |    ```bash
 9 |    gitty --repo microsoft/autogen issue 5212
10 |    ```
11 | 
12 | *Important*: Install the dependencies and set OpenAI API key:
13 | 
14 |    ```bash
15 |    uv sync --all-extras
16 |    source .venv/bin/activate
17 |    export OPENAI_API_KEY=sk-....
18 |    ```
19 | 


--------------------------------------------------------------------------------
/python/samples/gitty/src/gitty/__init__.py:
--------------------------------------------------------------------------------
1 | from .__main__ import main
2 | 
3 | __all__ = ["main"]
4 | 


--------------------------------------------------------------------------------
/python/samples/task_centric_memory/data_files/insights/add_topic.yaml:
--------------------------------------------------------------------------------
1 | # Advice created manually for solving the autogen_package task.
2 | 
3 | insight: 'When somebody builds something on autogen and wants to contribute it to autogen,
4 |   instead of creating a new autogen package, it''s better for them to implement it in a separate github repo,
5 |   then just add the autogen-extension topic to that repo.
6 |   That way their contribution will be automatically discoverable through autogen''s page on community extensions:  https://microsoft.github.io/autogen/dev/user-guide/extensions-user-guide/index.html'
7 | 


--------------------------------------------------------------------------------
/python/samples/task_centric_memory/data_files/insights/liar_advice.yaml:
--------------------------------------------------------------------------------
1 | # Advice created automatically for solving the 10_liars task.
2 | 
3 | insight: 'When solving logic puzzles, carefully consider all possible scenarios,
4 |   including the simplest ones, and remember that if everyone is lying,
5 |   their statements should naturally align with the known conditions without needing a truth-teller.
6 |   Always double-check that your conclusions don''t inadvertently introduce contradictions.'
7 | 


--------------------------------------------------------------------------------
/python/samples/task_centric_memory/data_files/tasks/10_liars.yaml:
--------------------------------------------------------------------------------
1 | # Similar to the 100 vampires task, for testing generalization from one to the other.
2 | 
3 | task_description: 'You ask ten people ''How many of you are liars?''
4 |   They all answer ''At least one of us is not a liar.''
5 |   You happen to know that at least one of them IS a liar.
6 |   How many of them are liars in total?'
7 | 
8 | expected_answer: All of them are liars.
9 | 


--------------------------------------------------------------------------------
/python/samples/task_centric_memory/data_files/tasks/autogen_package.yaml:
--------------------------------------------------------------------------------
1 | # Test where human advice is needed.
2 | 
3 | task_description: As a contribution to autogen, can I create a new autogen package for a copilot extension agent that I built on autogen?
4 | 
5 | expected_answer: It's best to have your agent in its own repo, then add the autogen-extension topic to that repo.
6 | 


--------------------------------------------------------------------------------
/python/samples/task_centric_memory/data_files/tasks/cell_towers_1.yaml:
--------------------------------------------------------------------------------
 1 | # File-free version of a GAIA L1 task.
 2 | 
 3 | task_description: You are a telecommunications engineer who wants to build cell phone towers on a stretch of road.
 4 |                   Houses are located at mile markers 16, 17, 19, 11, 9, 10, 2, 5, 4.
 5 |                   Each cell phone tower can cover houses located next to the road within a 4-mile radius.
 6 |                   Find the minimum number of cell phone towers needed to cover all houses next to the road.
 7 |                   Your answer should be a positive numerical integer value.
 8 | 
 9 | expected_answer: '2'
10 | 


--------------------------------------------------------------------------------
/python/samples/task_centric_memory/data_files/tasks/cell_towers_2.yaml:
--------------------------------------------------------------------------------
 1 | # Similar to the cell_towers_1 task.
 2 | 
 3 | task_description: You are a telecommunications engineer who wants to build cell phone towers on a stretch of road.
 4 |                   Houses are located at mile markers 17, 20, 19, 10, 11, 12, 3, 6.
 5 |                   Each cell phone tower can cover houses located next to the road within a 4-mile radius.
 6 |                   Find the minimum number of cell phone towers needed to cover all houses next to the road.
 7 |                   Your answer should be a positive numerical integer value.
 8 | 
 9 | expected_answer: '2'
10 | 


--------------------------------------------------------------------------------
/python/shared_tasks.toml:
--------------------------------------------------------------------------------
1 | [tool.poe.tasks]
2 | fmt = "ruff format"
3 | format.ref = "fmt"
4 | lint = "ruff check"
5 | mypy = "mypy --config-file $POE_ROOT/../../pyproject.toml src tests"
6 | pyright = "pyright"
7 | 


--------------------------------------------------------------------------------
/python/templates/new-package/cookiecutter.json:
--------------------------------------------------------------------------------
1 | {
2 |     "package_name": "my-project",
3 |     "version": "0.1.dev0",
4 |     "description": "My package description",
5 |     "depends_on_core": false,
6 |     "__final_destination": "../packages",
7 |     "__project_slug": "{{ cookiecutter.package_name.replace(' ', '_').replace('-', '_') }}"
8 | }


--------------------------------------------------------------------------------
/python/templates/new-package/hooks/post_gen_project.py:
--------------------------------------------------------------------------------
 1 | import os
 2 | import shutil
 3 | from pathlib import Path
 4 | import tomli_w
 5 | import tomllib
 6 | 
 7 | source_dir = os.getcwd()
 8 | target_dir = "{{ cookiecutter.__final_destination }}"
 9 | 
10 | shutil.move(source_dir, target_dir)
11 | 
12 | THIS_FILE_DIR = Path(__file__).parent
13 | 
14 | # Add the package to the workspace def
15 | 
16 | workspace_def_path = THIS_FILE_DIR / ".." / ".." / ".." / "pyproject.toml"
17 | 
18 | with workspace_def_path.open("rb") as f:
19 |     config = tomllib.load(f)
20 | 
21 | config["tool"]["uv"]["sources"]["{{ cookiecutter.package_name }}"] = {"workspace": True}
22 | 
23 | with workspace_def_path.open("wb") as f:
24 |     tomli_w.dump(config, f)
25 | 


--------------------------------------------------------------------------------
/python/templates/new-package/hooks/pre_gen_project.py:
--------------------------------------------------------------------------------
 1 | import re
 2 | import sys
 3 | from packaging import version
 4 | 
 5 | MODULE_REGEX = r"^[a-zA-Z][\-a-zA-Z0-9]+
quot;
 6 | 
 7 | package_name = "{{ cookiecutter.package_name }}"
 8 | 
 9 | at_least_one_error = False
10 | if not re.match(MODULE_REGEX, package_name):
11 |     print(f'ERROR: "{package_name}" must use kebab case')
12 |     at_least_one_error = True
13 | 
14 | packaging_version = "{{ cookiecutter.version }}"
15 | 
16 | # Check version format using version.VERSION_PATTERN
17 | if not re.match(version.VERSION_PATTERN, packaging_version, re.VERBOSE | re.IGNORECASE):
18 |     print(f'ERROR: "{packaging_version}" is not a valid version string')
19 |     at_least_one_error = True
20 | 
21 | if at_least_one_error:
22 |     sys.exit(1)
23 | 


--------------------------------------------------------------------------------
/python/templates/new-package/{{cookiecutter.package_name}}/README.md:
--------------------------------------------------------------------------------
1 | # {{cookiecutter.package_name}}
2 | 


--------------------------------------------------------------------------------
/python/templates/new-package/{{cookiecutter.package_name}}/src/{{cookiecutter.__project_slug}}/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/python/templates/new-package/{{cookiecutter.package_name}}/src/{{cookiecutter.__project_slug}}/__init__.py


--------------------------------------------------------------------------------
/python/templates/new-package/{{cookiecutter.package_name}}/src/{{cookiecutter.__project_slug}}/py.typed:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/microsoft/autogen/413d8f158cb0506a7cb6180b09f0d0c1b5162b1c/python/templates/new-package/{{cookiecutter.package_name}}/src/{{cookiecutter.__project_slug}}/py.typed


--------------------------------------------------------------------------------
/python/templates/new-package/{{cookiecutter.package_name}}/tests/test_example.py:
--------------------------------------------------------------------------------
1 | async def test_example() -> None:
2 |     assert True


--------------------------------------------------------------------------------
