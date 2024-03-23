[discord-url]: https://discord.gg/9Xpy2HGBuD

# MLC LLM


<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LLM</font></font></h1><a id="user-content-mlc-llm" class="anchor" aria-label="永久链接：MLC 法学硕士" href="#mlc-llm"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a href="https://llm.mlc.ai/docs" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">| </font></font><a href="https://blog.mlc.ai/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">博客</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">| </font></font><a href="https://discord.gg/9Xpy2HGBuD" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Discord</font></font></a></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">大型</font></font></strong><font style="vertical-align: inherit;"></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">语言</font></font></strong><font style="vertical-align: inherit;"><strong><font style="vertical-align: inherit;">模型</font></strong><font style="vertical-align: inherit;">的机器学习编译</font><strong><font style="vertical-align: inherit;">(</font></strong><font style="vertical-align: inherit;"> MLC </font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LLM</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> )是</font><font style="vertical-align: inherit;">一种高性能通用部署解决方案，允许使用具有编译器加速功能的本机 API 来本机部署任何大型</font><strong><font style="vertical-align: inherit;">语言</font></strong><font style="vertical-align: inherit;">模型</font><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">该项目的使命是让每个人都能够利用机器学习编译技术在每个人的设备上本地开发、优化和部署人工智能模型。</font></font><strong><font style="vertical-align: inherit;"></font></strong><font style="vertical-align: inherit;"></font><strong><font style="vertical-align: inherit;"></font></strong><font style="vertical-align: inherit;"></font><strong><font style="vertical-align: inherit;"></font></strong><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通用部署。</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MLC LLM 支持以下平台和硬件：</font></font></p>
<table>
  <thead>
    <tr>
      <th> </th>
      <th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AMD显卡</font></font></th>
      <th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">英伟达图形处理器</font></font></th>
      <th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">苹果GPU</font></font></th>
      <th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">英特尔GPU</font></font></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Linux / 操作系统</font></font></td>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✅ Vulkan、ROCm</font></font></td>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✅ 伏尔甘、CUDA</font></font></td>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✅ 伏尔甘</font></font></td>
    </tr>
    <tr>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">苹果系统</font></font></td>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✅ 金属 (dGPU)</font></font></td>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✅ 金属</font></font></td>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✅ 金属（iGPU）</font></font></td>
    </tr>
    <tr>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">网页浏览器</font></font></td>
      <td colspan="4"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✅ WebGPU 和 WASM</font></font></td>
    </tr>
    <tr>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">iOS/iPadOS</font></font></td>
      <td colspan="4"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✅ Apple A 系列 GPU 上的 Metal</font></font></td>
    </tr>
    <tr>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安卓</font></font></td>
      <td colspan="2"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✅ Adreno GPU 上的 OpenCL</font></font></td>
      <td colspan="2"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✅ Mali GPU 上的 OpenCL</font></font></td>
    </tr>
  </tbody>
</table>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可扩展。</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MLC LLM 可在 NVIDIA 和 AMD GPU、云和游戏 GPU 上普遍扩展。</font><font style="vertical-align: inherit;">下面展示了我们的单批解码性能，其中预填充 = 1，解码 = 256。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4 位 CodeLlama-34B 和 Llama2-70B 在两个 NVIDIA RTX 4090 和两个 AMD Radeon 7900 XTX 上的性能：</font></font></p>
<p dir="auto">
  <a target="_blank" rel="noopener noreferrer" href="https://github.com/mlc-ai/mlc-llm/blob/main/site/img/multi-gpu/figure-1.svg"><img src="https://github.com/mlc-ai/mlc-llm/raw/main/site/img/multi-gpu/figure-1.svg" width="40%" style="max-width: 100%;"></a>
  <a target="_blank" rel="noopener noreferrer" href="https://github.com/mlc-ai/mlc-llm/blob/main/site/img/multi-gpu/figure-3.svg"><img src="https://github.com/mlc-ai/mlc-llm/raw/main/site/img/multi-gpu/figure-3.svg" width="30%" style="max-width: 100%;"></a>
</p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 A100-80G-PCIe 和 A10G-24G-PCIe 上扩展 fp16 和 4 位 CodeLlama-34 和 Llama2-70B，最多 8 个 GPU：</font></font></p>
<p dir="auto">
  <a target="_blank" rel="noopener noreferrer" href="https://github.com/mlc-ai/mlc-llm/blob/main/site/img/multi-gpu/figure-2.svg"><img src="https://github.com/mlc-ai/mlc-llm/raw/main/site/img/multi-gpu/figure-2.svg" width="100%" style="max-width: 100%;"></a>
</p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">消息</font></font></h2><a id="user-content-news" class="anchor" aria-label="永久链接：新闻" href="#news"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[10/18/2023] </font></font><a href="https://blog.mlc.ai/2023/10/19/Scalable-Language-Model-Inference-on-Multiple-NVDIA-AMD-GPUs" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[帖子]</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> CUDA 和 ROCm 的可扩展多 GPU 支持已正式发布。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[09/02/2023] 预构建的 ROCm 5.7 和 CUDA 12.2 包</font></font><a href="https://llm.mlc.ai/docs/install/tvm.html#option-1-prebuilt-package" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可用</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[08/25/2023] CodeLlama 支持已启动。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[08/14/2023] </font></font><a href="https://blog.mlc.ai/2023/08/09/GPU-Accelerated-LLM-on-Orange-Pi" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[帖子]</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> Orange Pi 上已支持 Mali GPU。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[08/09/2023] </font></font><a href="https://blog.mlc.ai/2023/08/09/Making-AMD-GPUs-competitive-for-LLM-inference" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[帖子]</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ROCm 后端已成熟使用。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[08/02/2023] </font></font><a href="https://github.com/mlc-ai/llm-perf-bench/"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Dockerfile</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发布用于 CUDA 性能基准测试。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[07/19/2023] 对 Llama2-7B/13B/70B 的支持已增加。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[05/22/2023] </font></font><a href="https://blog.mlc.ai/2023/05/22/bringing-open-large-language-models-to-consumer-devices" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[帖子]</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> RedPajama 支持已启动。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[05/08/2023] </font></font><a href="https://blog.mlc.ai/2023/05/08/bringing-hardware-accelerated-language-models-to-android-devices" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[帖子]</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> MLC LLM 现已在 Android 上提供。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[05/01/2023] </font></font><a href="https://blog.mlc.ai/2023/05/01/bringing-accelerated-llm-to-consumer-hardware" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[帖子]</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> MLC LLM 与 Metal、Vulkan 和 CUDA 后端一起发布。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[04/14/2023] </font></font><a href="https://github.com/mlc-ai/web-llm"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">WebLLM</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 MLC LLM 之前发布，具有 WebGPU 和 WebAssembly 后端。</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">入门</font></font></h2><a id="user-content-getting-started" class="anchor" aria-label="永久链接：开始使用" href="#getting-started"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请访问我们的</font></font><a href="https://llm.mlc.ai/docs/index.html#getting-started" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以获取详细说明。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">型号支持</font></font></h2><a id="user-content-model-support" class="anchor" aria-label="永久链接：模型支持" href="#model-support"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MLC LLM 支持多种模型架构和变体。</font><font style="vertical-align: inherit;">我们有以下预构建的，您可以使用现成的。</font><font style="vertical-align: inherit;">请访问</font></font><a href="https://llm.mlc.ai/docs/prebuilt_models.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">预构建模型</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以查看完整列表，并</font></font><a href="https://llm.mlc.ai/docs/compilation/compile_models.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过 MLC 编译模型</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以了解如何使用未在此列表中的模型。</font></font></p>
<table>
  <thead>
    <tr>
      <th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">建筑学</font></font></th>
      <th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">预建模型变体</font></font></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">骆驼</font></font></td>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Llama-2、Code Llama、Vicuna、WizardLM、WizardMath、OpenOrca Platypus2、FlagAlpha Llama-2 中文、georgesung Llama-2 未经审查</font></font></td>
    </tr>
    <tr>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GPT-NeoX</font></font></td>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">红色睡衣</font></font></td>
    </tr>
    <tr>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GPT-J</font></font></td>
      <td></td>
    </tr>
    <tr>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RWKV</font></font></td>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RWKV-乌鸦</font></font></td>
    </tr>
    <tr>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">迷你GPT</font></font></td>
      <td></td>
    </tr>
    <tr>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GPT大码</font></font></td>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">向导编码器</font></font></td>
    </tr>
    <tr>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">聊天GLM</font></font></td>
      <td></td>
    </tr>
    <tr>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">稳定LM</font></font></td>
      <td></td>
    </tr>
    <tr>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">米斯特拉尔</font></font></td>
      <td></td>
    </tr>
    <tr>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">披</font></font></td>
      <td></td>
    </tr>
  </tbody>
</table>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通用部署 API</font></font></h2><a id="user-content-universal-deployment-apis" class="anchor" aria-label="永久链接：通用部署 API" href="#universal-deployment-apis"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MLC LLM 提供多组跨平台和环境的 API。</font><font style="vertical-align: inherit;">这些包括</font></font></p>
<ul dir="auto">
<li><a href="https://llm.mlc.ai/docs/deploy/python.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Python API</font></font></a></li>
<li><a href="https://llm.mlc.ai/docs/deploy/rest.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">兼容 OpenAI 的 Rest-API</font></font></a></li>
<li><a href="https://llm.mlc.ai/docs/deploy/cli.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">C++ API</font></font></a></li>
<li><a href="https://llm.mlc.ai/docs/deploy/javascript.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JavaScript API</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://github.com/mlc-ai/web-llm"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Web LLM</font></font></a></li>
<li><a href="https://llm.mlc.ai/docs/deploy/ios.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">适用于 iOS 应用程序的 Swift API</font></font></a></li>
<li><a href="https://llm.mlc.ai/docs/deploy/android.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Java API 和 Android 应用程序</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">引文</font></font></h2><a id="user-content-citation" class="anchor" aria-label="永久链接：引文" href="#citation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您觉得有用，请考虑引用我们的项目：</font></font></p>
<div class="highlight highlight-text-bibtex notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">@software</span>{<span class="pl-en">mlc-llm</span>,
    <span class="pl-s">author</span> = <span class="pl-s"><span class="pl-pds">{</span>MLC team<span class="pl-pds">}</span></span>,
    <span class="pl-s">title</span> = <span class="pl-s"><span class="pl-pds">{</span>{MLC-LLM}<span class="pl-pds">}</span></span>,
    <span class="pl-s">url</span> = <span class="pl-s"><span class="pl-pds">{</span>https://github.com/mlc-ai/mlc-llm<span class="pl-pds">}</span></span>,
    <span class="pl-s">year</span> = <span class="pl-s"><span class="pl-pds">{</span>2023<span class="pl-pds">}</span></span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="@software{mlc-llm,
    author = {MLC team},
    title = {{MLC-LLM}},
    url = {https://github.com/mlc-ai/mlc-llm},
    year = {2023}
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MLC LLM的基础技术包括：</font></font></p>
<details>
  <summary><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">参考文献（点击展开）</font></font></summary>
<div class="highlight highlight-text-bibtex notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">@inproceedings</span>{<span class="pl-en">tensorir</span>,
    <span class="pl-s">author</span> = <span class="pl-s"><span class="pl-pds">{</span>Feng, Siyuan and Hou, Bohan and Jin, Hongyi and Lin, Wuwei and Shao, Junru and Lai, Ruihang and Ye, Zihao and Zheng, Lianmin and Yu, Cody Hao and Yu, Yong and Chen, Tianqi<span class="pl-pds">}</span></span>,
    <span class="pl-s">title</span> = <span class="pl-s"><span class="pl-pds">{</span>TensorIR: An Abstraction for Automatic Tensorized Program Optimization<span class="pl-pds">}</span></span>,
    <span class="pl-s">year</span> = <span class="pl-s"><span class="pl-pds">{</span>2023<span class="pl-pds">}</span></span>,
    <span class="pl-s">isbn</span> = <span class="pl-s"><span class="pl-pds">{</span>9781450399166<span class="pl-pds">}</span></span>,
    <span class="pl-s">publisher</span> = <span class="pl-s"><span class="pl-pds">{</span>Association for Computing Machinery<span class="pl-pds">}</span></span>,
    <span class="pl-s">address</span> = <span class="pl-s"><span class="pl-pds">{</span>New York, NY, USA<span class="pl-pds">}</span></span>,
    <span class="pl-s">url</span> = <span class="pl-s"><span class="pl-pds">{</span>https://doi.org/10.1145/3575693.3576933<span class="pl-pds">}</span></span>,
    <span class="pl-s">doi</span> = <span class="pl-s"><span class="pl-pds">{</span>10.1145/3575693.3576933<span class="pl-pds">}</span></span>,
    <span class="pl-s">booktitle</span> = <span class="pl-s"><span class="pl-pds">{</span>Proceedings of the 28th ACM International Conference on Architectural Support for Programming Languages and Operating Systems, Volume 2<span class="pl-pds">}</span></span>,
    <span class="pl-s">pages</span> = <span class="pl-s"><span class="pl-pds">{</span>804–817<span class="pl-pds">}</span></span>,
    <span class="pl-s">numpages</span> = <span class="pl-s"><span class="pl-pds">{</span>14<span class="pl-pds">}</span></span>,
    <span class="pl-s">keywords</span> = <span class="pl-s"><span class="pl-pds">{</span>Tensor Computation, Machine Learning Compiler, Deep Neural Network<span class="pl-pds">}</span></span>,
    <span class="pl-s">location</span> = <span class="pl-s"><span class="pl-pds">{</span>Vancouver, BC, Canada<span class="pl-pds">}</span></span>,
    <span class="pl-s">series</span> = <span class="pl-s"><span class="pl-pds">{</span>ASPLOS 2023<span class="pl-pds">}</span></span>
}

<span class="pl-k">@inproceedings</span>{<span class="pl-en">metaschedule</span>,
    <span class="pl-s">author</span> = <span class="pl-s"><span class="pl-pds">{</span>Shao, Junru and Zhou, Xiyou and Feng, Siyuan and Hou, Bohan and Lai, Ruihang and Jin, Hongyi and Lin, Wuwei and Masuda, Masahiro and Yu, Cody Hao and Chen, Tianqi<span class="pl-pds">}</span></span>,
    <span class="pl-s">booktitle</span> = <span class="pl-s"><span class="pl-pds">{</span>Advances in Neural Information Processing Systems<span class="pl-pds">}</span></span>,
    <span class="pl-s">editor</span> = <span class="pl-s"><span class="pl-pds">{</span>S. Koyejo and S. Mohamed and A. Agarwal and D. Belgrave and K. Cho and A. Oh<span class="pl-pds">}</span></span>,
    <span class="pl-s">pages</span> = <span class="pl-s"><span class="pl-pds">{</span>35783--35796<span class="pl-pds">}</span></span>,
    <span class="pl-s">publisher</span> = <span class="pl-s"><span class="pl-pds">{</span>Curran Associates, Inc.<span class="pl-pds">}</span></span>,
    <span class="pl-s">title</span> = <span class="pl-s"><span class="pl-pds">{</span>Tensor Program Optimization with Probabilistic Programs<span class="pl-pds">}</span></span>,
    <span class="pl-s">url</span> = <span class="pl-s"><span class="pl-pds">{</span>https://proceedings.neurips.cc/paper_files/paper/2022/file/e894eafae43e68b4c8dfdacf742bcbf3-Paper-Conference.pdf<span class="pl-pds">}</span></span>,
    <span class="pl-s">volume</span> = <span class="pl-s"><span class="pl-pds">{</span>35<span class="pl-pds">}</span></span>,
    <span class="pl-s">year</span> = <span class="pl-s"><span class="pl-pds">{</span>2022<span class="pl-pds">}</span></span>
}

<span class="pl-k">@inproceedings</span>{<span class="pl-en">tvm</span>,
    <span class="pl-s">author</span> = <span class="pl-s"><span class="pl-pds">{</span>Tianqi Chen and Thierry Moreau and Ziheng Jiang and Lianmin Zheng and Eddie Yan and Haichen Shen and Meghan Cowan and Leyuan Wang and Yuwei Hu and Luis Ceze and Carlos Guestrin and Arvind Krishnamurthy<span class="pl-pds">}</span></span>,
    <span class="pl-s">title</span> = <span class="pl-s"><span class="pl-pds">{</span>{TVM}: An Automated {End-to-End} Optimizing Compiler for Deep Learning<span class="pl-pds">}</span></span>,
    <span class="pl-s">booktitle</span> = <span class="pl-s"><span class="pl-pds">{</span>13th USENIX Symposium on Operating Systems Design and Implementation (OSDI 18)<span class="pl-pds">}</span></span>,
    <span class="pl-s">year</span> = <span class="pl-s"><span class="pl-pds">{</span>2018<span class="pl-pds">}</span></span>,
    <span class="pl-s">isbn</span> = <span class="pl-s"><span class="pl-pds">{</span>978-1-939133-08-3<span class="pl-pds">}</span></span>,
    <span class="pl-s">address</span> = <span class="pl-s"><span class="pl-pds">{</span>Carlsbad, CA<span class="pl-pds">}</span></span>,
    <span class="pl-s">pages</span> = <span class="pl-s"><span class="pl-pds">{</span>578--594<span class="pl-pds">}</span></span>,
    <span class="pl-s">url</span> = <span class="pl-s"><span class="pl-pds">{</span>https://www.usenix.org/conference/osdi18/presentation/chen<span class="pl-pds">}</span></span>,
    <span class="pl-s">publisher</span> = <span class="pl-s"><span class="pl-pds">{</span>USENIX Association<span class="pl-pds">}</span></span>,
    <span class="pl-s">month</span> = oct,
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="@inproceedings{tensorir,
    author = {Feng, Siyuan and Hou, Bohan and Jin, Hongyi and Lin, Wuwei and Shao, Junru and Lai, Ruihang and Ye, Zihao and Zheng, Lianmin and Yu, Cody Hao and Yu, Yong and Chen, Tianqi},
    title = {TensorIR: An Abstraction for Automatic Tensorized Program Optimization},
    year = {2023},
    isbn = {9781450399166},
    publisher = {Association for Computing Machinery},
    address = {New York, NY, USA},
    url = {https://doi.org/10.1145/3575693.3576933},
    doi = {10.1145/3575693.3576933},
    booktitle = {Proceedings of the 28th ACM International Conference on Architectural Support for Programming Languages and Operating Systems, Volume 2},
    pages = {804–817},
    numpages = {14},
    keywords = {Tensor Computation, Machine Learning Compiler, Deep Neural Network},
    location = {Vancouver, BC, Canada},
    series = {ASPLOS 2023}
}

@inproceedings{metaschedule,
    author = {Shao, Junru and Zhou, Xiyou and Feng, Siyuan and Hou, Bohan and Lai, Ruihang and Jin, Hongyi and Lin, Wuwei and Masuda, Masahiro and Yu, Cody Hao and Chen, Tianqi},
    booktitle = {Advances in Neural Information Processing Systems},
    editor = {S. Koyejo and S. Mohamed and A. Agarwal and D. Belgrave and K. Cho and A. Oh},
    pages = {35783--35796},
    publisher = {Curran Associates, Inc.},
    title = {Tensor Program Optimization with Probabilistic Programs},
    url = {https://proceedings.neurips.cc/paper_files/paper/2022/file/e894eafae43e68b4c8dfdacf742bcbf3-Paper-Conference.pdf},
    volume = {35},
    year = {2022}
}

@inproceedings{tvm,
    author = {Tianqi Chen and Thierry Moreau and Ziheng Jiang and Lianmin Zheng and Eddie Yan and Haichen Shen and Meghan Cowan and Leyuan Wang and Yuwei Hu and Luis Ceze and Carlos Guestrin and Arvind Krishnamurthy},
    title = {{TVM}: An Automated {End-to-End} Optimizing Compiler for Deep Learning},
    booktitle = {13th USENIX Symposium on Operating Systems Design and Implementation (OSDI 18)},
    year = {2018},
    isbn = {978-1-939133-08-3},
    address = {Carlsbad, CA},
    pages = {578--594},
    url = {https://www.usenix.org/conference/osdi18/presentation/chen},
    publisher = {USENIX Association},
    month = oct,
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</details>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">链接</font></font></h2><a id="user-content-links" class="anchor" aria-label="永久链接： 链接" href="#links"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可能想查看我们的在线公共</font></font><a href="https://mlc.ai" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机器学习编译课程</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，以系统地了解我们的方法。</font></font></li>
<li><a href="https://webllm.mlc.ai/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">WebLLM</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是一个使用 MLC LLM 的 WebGPU 和 WebAssembly 后端的配套项目。</font></font></li>
<li><a href="https://websd.mlc.ai/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">WebStableDiffusion</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是具有 WebGPU 后端的扩散模型的配套项目。</font></font></li>
</ul>
</article></div>
