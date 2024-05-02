<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/OpenGVLab/InternVL/assets/8529570/5aa4cda8-b453-40a0-9336-17012b430ae8"><img width="60" alt="图像" src="https://github.com/OpenGVLab/InternVL/assets/8529570/5aa4cda8-b453-40a0-9336-17012b430ae8" style="max-width: 100%;"></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">InternVL系列：通过开源套件缩小与商业多式联运模型的差距——GPT-4V的开创性开源替代品</font></font></h1><a id="user-content--internvl-family-closing-the-gap-to-commercial-multimodal-models-with-open-source-suites--a-pioneering-open-source-alternative-to-gpt-4v" class="anchor" aria-label="永久链接：InternVL 系列：利用开源套件缩小与商业多式联运模型的差距——GPT-4V 的开创性开源替代方案" href="#-internvl-family-closing-the-gap-to-commercial-multimodal-models-with-open-source-suites--a-pioneering-open-source-alternative-to-gpt-4v"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[</font></font><a href="/OpenGVLab/InternVL/blob/main/BLOG.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更新博客</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">] [</font></font><a href="https://arxiv.org/abs/2312.14238" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">论文</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">] [ </font></font><a href="https://arxiv.org/abs/2404.16821" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">InternVL 1.5 技术报告</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">] [</font></font><a href="https://internvl.opengvlab.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">聊天演示</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">] </font></font><a href="https://huggingface.co/spaces/OpenGVLab/InternVL" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[HuggingFace 演示 ]</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> [</font></font><a href="#quick-start-with-huggingface"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">快速入门</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">] [</font></font><a href="https://zhuanlan.zhihu.com/p/675877376" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中文阅读</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">]</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">新闻🚀🚀🚀</font></font></h2><a id="user-content-news" class="anchor" aria-label="永久链接：新闻🚀🚀🚀" href="#news"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><code>2024/04/28</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：我们发布了 InternVL-Chat-V1-5 的 INT8 版本，请参见</font></font><a href="https://huggingface.co/OpenGVLab/InternVL-Chat-V1-5-Int8" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此处</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><code>2024/04/28</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：我们在 Infographics VQA 基准测试中实现了 SOTA 性能 (75.74)，请参见</font></font><a href="https://rrc.cvc.uab.es/?ch=17&amp;com=evaluation&amp;task=3" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此处</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><code>2024/04/18</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：InternVL-Chat-V1.5已在</font></font><a href="https://huggingface.co/OpenGVLab/InternVL-Chat-V1-5" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HF link</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发布，在MMMU、DocVQA、ChartQA、MathVista等各种基准测试上接近GPT-4V和Gemini Pro的性能。</font></font></li>
<li><code>2024/02/27</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：InternVL 被 CVPR 2024 接受！ 🎉</font></font></li>
<li><code>2024/02/24</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：InternVL-Chat 模型已包含在</font></font><a href="https://github.com/open-compass/VLMEvalKit"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">VLMEvalKit</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中。</font></font></li>
<li><code>2024/02/21</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font><a href="https://huggingface.co/OpenGVLab/InternVL-Chat-V1-2-Plus" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">InternVL-Chat-V1.2-Plus</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 MathVista (59.9)、MMBench (83.8) 和 MMVP (58.7) 上实现了 SOTA 性能。请参阅我们的</font></font><a href="/OpenGVLab/InternVL/blob/main/BLOG.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">博客</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">了解更多详细信息。</font></font></li>
<li><code>2024/02/12</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">: InternVL-Chat-V1.2 已发布。它在 MMMU val 上达到 51.6，在 MMBench 测试上达到 82.3。有关更多详细信息，请参阅我们的</font></font><a href="/OpenGVLab/InternVL/blob/main/BLOG.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">博客</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://github.com/OpenGVLab/InternVL/tree/main/internvl_chat#prepare-training-datasets"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SFT 数据</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或尝试我们的</font></font><a href="https://internvl.opengvlab.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">演示</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。该模型现已在</font></font><a href="https://huggingface.co/OpenGVLab/InternVL-Chat-V1-2" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HuggingFace</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上提供，并且训练/评估数据和脚本都是开源的。</font></font></li>
<li><code>2024/02/04</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font><a href="https://huggingface.co/OpenGVLab/InternVL-Chat-V1-1" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">InternVL-Chat-V1.1在</font></font></a><font style="vertical-align: inherit;"></font><a href="https://github.com/tsb0601/MMVP"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MMVP</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上达到 44.67% </font><font style="vertical-align: inherit;">，高于 GPT-4V！</font></font></li>
<li><code>2024/01/27</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：我们发布了448分辨率模型，在MMBench dev上达到了76.6，参见</font></font><a href="https://github.com/OpenGVLab/InternVL/tree/main/internvl_chat#-evaluation-chinese-models"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这里</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><code>2024/01/24</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">: InternVL-Chat-V1.1 发布，支持中文，OCR 能力更强，请看</font></font><a href="https://huggingface.co/OpenGVLab/InternVL-Chat-V1-1" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这里</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或尝试我们的</font></font><a href="https://internvl.opengvlab.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">演示</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><code>2024/01/16</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：我们发布了与 DeepSpeed 集成的</font></font><a href="https://github.com/OpenGVLab/InternVL-MMDetSeg"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">定制 mmcv/mmsegmentation/mmdetection 代码</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，可用于训练大规模对象检测和语义分割模型。</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件</font></font></h2><a id="user-content-documents" class="anchor" aria-label="永久链接：文档" href="#documents"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何安装InternVL？</font></font><a href="/OpenGVLab/InternVL/blob/main/INSTALLATION.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[关联]</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何微调InternVL？</font></font><a href="/OpenGVLab/InternVL/blob/main/internvl_chat/README.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[关联]</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何评价InternVL-Chat-V1-5？</font></font><a href="/OpenGVLab/InternVL/blob/main/document/how_to_evaluate_internvl_chat_1_5.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[关联]</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何使用 VLMEvalKit 评估 InternVL-Chat-V1-5？ （推荐）</font></font><a href="/OpenGVLab/InternVL/blob/main/document/how_to_evaluate_internvl_chat_1_5_using_vlmevalkit.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[链接]</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何部署本地demo？</font></font><a href="/OpenGVLab/InternVL/blob/main/document/how_to_deploy_a_local_demo.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[关联]</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与 SOTA VLLM 相比</font></font></h2><a id="user-content-compared-with-sota-vllms" class="anchor" aria-label="永久链接：与 SOTA VLLM 相比" href="#compared-with-sota-vllms"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p align="center" dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://private-user-images.githubusercontent.com/23737120/326237019-38e8a632-229c-4b20-b7e1-77299dfc6cee.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTQ2MzMyNjksIm5iZiI6MTcxNDYzMjk2OSwicGF0aCI6Ii8yMzczNzEyMC8zMjYyMzcwMTktMzhlOGE2MzItMjI5Yy00YjIwLWI3ZTEtNzcyOTlkZmM2Y2VlLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA1MDIlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNTAyVDA2NTYwOVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTc5Y2ViZGRjMGQzYjM1NzE5NDdhMzRhMzE1MjkwOGIxNTNmNzBhZjI3ZjRlZGI0OWY3MDZhOTc1MWUzNjUzNjAmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.PP2axrJoagSEd-0NO1Wc-RXuS_gyiH5vl6b1WGp78-w"><img width="500" alt="图像" src="https://private-user-images.githubusercontent.com/23737120/326237019-38e8a632-229c-4b20-b7e1-77299dfc6cee.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTQ2MzMyNjksIm5iZiI6MTcxNDYzMjk2OSwicGF0aCI6Ii8yMzczNzEyMC8zMjYyMzcwMTktMzhlOGE2MzItMjI5Yy00YjIwLWI3ZTEtNzcyOTlkZmM2Y2VlLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA1MDIlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNTAyVDA2NTYwOVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTc5Y2ViZGRjMGQzYjM1NzE5NDdhMzRhMzE1MjkwOGIxNTNmNzBhZjI3ZjRlZGI0OWY3MDZhOTc1MWUzNjUzNjAmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.PP2axrJoagSEd-0NO1Wc-RXuS_gyiH5vl6b1WGp78-w" style="max-width: 100%;"></a></p>
<a target="_blank" rel="noopener noreferrer" href="https://private-user-images.githubusercontent.com/23737120/326092358-e9065a58-86fa-47ef-be9a-eb734532e73f.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTQ2MzMyNjksIm5iZiI6MTcxNDYzMjk2OSwicGF0aCI6Ii8yMzczNzEyMC8zMjYwOTIzNTgtZTkwNjVhNTgtODZmYS00N2VmLWJlOWEtZWI3MzQ1MzJlNzNmLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA1MDIlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNTAyVDA2NTYwOVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPThiYzI4MzY3NzliNDY5Mzk4MjYzZjgxMjVjMzM3ZjYzZGQ0MWU0Y2EzNmYwMGZmZWQxNjI4YjA4ZjliZTQ3YzcmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.6YPHsRhTcU3bxcbhPK6qSJddHBovWsMkHWWVKZ42XVA"><img width="1229" alt="图像" src="https://private-user-images.githubusercontent.com/23737120/326092358-e9065a58-86fa-47ef-be9a-eb734532e73f.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTQ2MzMyNjksIm5iZiI6MTcxNDYzMjk2OSwicGF0aCI6Ii8yMzczNzEyMC8zMjYwOTIzNTgtZTkwNjVhNTgtODZmYS00N2VmLWJlOWEtZWI3MzQ1MzJlNzNmLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA1MDIlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNTAyVDA2NTYwOVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPThiYzI4MzY3NzliNDY5Mzk4MjYzZjgxMjVjMzM3ZjYzZGQ0MWU0Y2EzNmYwMGZmZWQxNjI4YjA4ZjliZTQ3YzcmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.6YPHsRhTcU3bxcbhPK6qSJddHBovWsMkHWWVKZ42XVA" style="max-width: 100%;"></a>
<a target="_blank" rel="noopener noreferrer" href="https://private-user-images.githubusercontent.com/23737120/326576629-2b4f2978-36ea-4065-841d-3651c58955ed.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTQ2MzMyNjksIm5iZiI6MTcxNDYzMjk2OSwicGF0aCI6Ii8yMzczNzEyMC8zMjY1NzY2MjktMmI0ZjI5NzgtMzZlYS00MDY1LTg0MWQtMzY1MWM1ODk1NWVkLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA1MDIlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNTAyVDA2NTYwOVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTgxZjM1MzNjNjUyZjQ1Y2UwMTM2ZTdiM2MwN2Y1ZGM2YzM1MDlhNzE3YTc3YmM3MzlkODE1NDNkM2FlZDliMDEmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.Zag5m72fnWI-VzIZB2_BLDVBco29umed9vB9Gw0Qdeg"><img width="1229" alt="图像" src="https://private-user-images.githubusercontent.com/23737120/326576629-2b4f2978-36ea-4065-841d-3651c58955ed.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTQ2MzMyNjksIm5iZiI6MTcxNDYzMjk2OSwicGF0aCI6Ii8yMzczNzEyMC8zMjY1NzY2MjktMmI0ZjI5NzgtMzZlYS00MDY1LTg0MWQtMzY1MWM1ODk1NWVkLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA1MDIlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNTAyVDA2NTYwOVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTgxZjM1MzNjNjUyZjQ1Y2UwMTM2ZTdiM2MwN2Y1ZGM2YzM1MDlhNzE3YTc3YmM3MzlkODE1NDNkM2FlZDliMDEmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.Zag5m72fnWI-VzIZB2_BLDVBco29umed9vB9Gw0Qdeg" style="max-width: 100%;"></a>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">什么是InternVL？</font></font></h2><a id="user-content-what-is-internvl" class="anchor" aria-label="永久链接：什么是 InternVL？" href="#what-is-internvl"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">InternVL 将 ViT 参数扩展到</font></font><em><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">6B 参数</font></font></strong></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，并将其与 LLM 对齐。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型动物园</font></font></h2><a id="user-content-model-zoo" class="anchor" aria-label="永久链接：模型动物园" href="#model-zoo"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">视觉大语言模型</font></font></strong></p>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">日期</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">笔记</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实习生VL−聊天−V1.5-Int8</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2024年4月28日</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🤗</font></font><a href="https://huggingface.co/OpenGVLab/InternVL-Chat-V1-5-Int8" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">高频链接</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">InternVL-Chat-V1-5的INT8版本</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实习生VL−聊天−V1.5</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2024年4月18日</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🤗</font></font><a href="https://huggingface.co/OpenGVLab/InternVL-Chat-V1-5" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">高频链接</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持4K图像；超强OCR；在 MMMU、DocVQA、ChartQA、MathVista 等各种基准上接近 GPT-4V 和 Gemini Pro 的性能。（🔥新）</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实习生VL−聊天−V1.2−Plus</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2024年2月21日</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🤗</font></font><a href="https://huggingface.co/OpenGVLab/InternVL-Chat-V1-2-Plus" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">高频链接</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SFT数据更多更强</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实习生VL−聊天−V1.2</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2024年2月11日</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🤗</font></font><a href="https://huggingface.co/OpenGVLab/InternVL-Chat-V1-2" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">高频链接</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LLM 升级至 34B</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实习生VL−聊天−V1.1</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2024年1月24日</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🤗</font></font><a href="https://huggingface.co/OpenGVLab/InternVL-Chat-V1-1" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">高频链接</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持中文，OCR更强大</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实习生VL−聊天−19B−448px</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2024.02.03</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🤗</font></font><a href="https://huggingface.co/OpenGVLab/InternVL-Chat-ViT-6B-Vicuna-13B-448px" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">高频链接</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">448分辨率</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实习生VL−聊天−19B</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2023年12月25日</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🤗</font></font><a href="https://huggingface.co/OpenGVLab/InternVL-Chat-ViT-6B-Vicuna-13B" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">高频链接</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">英语多模态对话</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实习生VL−聊天−13B</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2023年12月25日</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🤗</font></font><a href="https://huggingface.co/OpenGVLab/InternVL-Chat-ViT-6B-Vicuna-7B" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">高频链接</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">英语多模态对话</font></font></td>
</tr>
</tbody>
</table>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">视觉语言基础模型</font></font></strong></p>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">日期</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">笔记</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实习生ViT−6B−448px−V1.5</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2024年4月20日</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🤗</font></font><a href="https://huggingface.co/OpenGVLab/InternViT-6B-448px-V1-5" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">高频链接</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持动态分辨率，超强OCR（🔥新）</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实习生ViT−6B−448px−V1.2</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2024年2月11日</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🤗</font></font><a href="https://huggingface.co/OpenGVLab/InternViT-6B-448px-V1-2" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">高频链接</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">448分辨率</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实习生ViT−6B−448px−V1.0</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2024年1月30日</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🤗</font></font><a href="https://huggingface.co/OpenGVLab/InternViT-6B-448px-V1-0" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">高频链接</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">448分辨率</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实习生ViT−6B−224px</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2023年12月22日</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🤗</font></font><a href="https://huggingface.co/OpenGVLab/InternViT-6B-224px" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">高频链接</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">视觉基础模型</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实习生VL−14B−224px</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2023年12月22日</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🤗</font></font><a href="https://huggingface.co/OpenGVLab/InternVL-14B-224px" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">高频链接</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">视觉语言基础模型</font></font></td>
</tr>
</tbody>
</table>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">InternVL 能做什么？</font></font></h2><a id="user-content-what-can-internvl-do" class="anchor" aria-label="永久链接：InternVL 可以做什么？" href="#what-can-internvl-do"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<details>
  <summary><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">视觉感知（点击展开）</font></font></summary>
<ul dir="auto">
<li>
<p dir="auto">Linear-Probe Image Classification <a href="/OpenGVLab/InternVL/blob/main/classification#-evaluation">[see details]</a></p>
<p dir="auto">ViT-22B uses the private JFT-3B dataset.</p>
<table>
<thead>
<tr>
<th>method</th>
<th align="center">#param</th>
<th align="center">IN-1K</th>
<th align="center">IN-ReaL</th>
<th align="center">IN-V2</th>
<th align="center">IN-A</th>
<th align="center">IN-R</th>
<th align="center">IN-Sketch</th>
</tr>
</thead>
<tbody>
<tr>
<td>OpenCLIP-G</td>
<td align="center">1.8B</td>
<td align="center">86.2</td>
<td align="center">89.4</td>
<td align="center">77.2</td>
<td align="center">63.8</td>
<td align="center">87.8</td>
<td align="center">66.4</td>
</tr>
<tr>
<td>DINOv2-g</td>
<td align="center">1.1B</td>
<td align="center">86.5</td>
<td align="center">89.6</td>
<td align="center">78.4</td>
<td align="center">75.9</td>
<td align="center">78.8</td>
<td align="center">62.5</td>
</tr>
<tr>
<td>EVA-01-CLIP-g</td>
<td align="center">1.1B</td>
<td align="center">86.5</td>
<td align="center">89.3</td>
<td align="center">77.4</td>
<td align="center">70.5</td>
<td align="center">87.7</td>
<td align="center">63.1</td>
</tr>
<tr>
<td>MAWS-ViT-6.5B</td>
<td align="center">6.5B</td>
<td align="center">87.8</td>
<td align="center">-</td>
<td align="center">-</td>
<td align="center">-</td>
<td align="center">-</td>
<td align="center">-</td>
</tr>
<tr>
<td>ViT-22B*</td>
<td align="center">21.7B</td>
<td align="center">89.5</td>
<td align="center">90.9</td>
<td align="center">83.2</td>
<td align="center">83.8</td>
<td align="center">87.4</td>
<td align="center">−</td>
</tr>
<tr>
<td>InternViT-6B (ours)</td>
<td align="center">5.9B</td>
<td align="center">88.2</td>
<td align="center">90.4</td>
<td align="center">79.9</td>
<td align="center">77.5</td>
<td align="center">89.8</td>
<td align="center">69.1</td>
</tr>
</tbody>
</table>
</li>
<li>
<p dir="auto">Semantic Segmentation <a href="/OpenGVLab/InternVL/blob/main/segmentation#-evaluation">[see details]</a></p>
<table>
<thead>
<tr>
<th>method</th>
<th align="center">decoder</th>
<th align="center">#param (train/total)</th>
<th align="center">crop size</th>
<th>mIoU</th>
</tr>
</thead>
<tbody>
<tr>
<td>OpenCLIP-G (frozen)</td>
<td align="center">Linear</td>
<td align="center">0.3M / 1.8B</td>
<td align="center">512</td>
<td>39.3</td>
</tr>
<tr>
<td>ViT-22B (frozen)</td>
<td align="center">Linear</td>
<td align="center">0.9M / 21.7B</td>
<td align="center">504</td>
<td>34.6</td>
</tr>
<tr>
<td>InternViT-6B (frozen)</td>
<td align="center">Linear</td>
<td align="center">0.5M / 5.9B</td>
<td align="center">504</td>
<td>47.2 (+12.6)</td>
</tr>
<tr>
<td>ViT-22B (frozen)</td>
<td align="center">UperNet</td>
<td align="center">0.8B / 22.5B</td>
<td align="center">504</td>
<td>52.7</td>
</tr>
<tr>
<td>InternViT-6B (frozen)</td>
<td align="center">UperNet</td>
<td align="center">0.4B / 6.3B</td>
<td align="center">504</td>
<td>54.9 (+2.2)</td>
</tr>
<tr>
<td>ViT-22B</td>
<td align="center">UperNet</td>
<td align="center">22.5B / 22.5B</td>
<td align="center">504</td>
<td>55.3</td>
</tr>
<tr>
<td>InternViT-6B</td>
<td align="center">UperNet</td>
<td align="center">6.3B / 6.3B</td>
<td align="center">504</td>
<td>58.9 (+3.6)</td>
</tr>
</tbody>
</table>
</li>
<li>
<p dir="auto">Zero-Shot Image Classification <a href="/OpenGVLab/InternVL/blob/main/clip_benchmark#imagenet-variants-and-objectnet">[see details]</a></p>
<table>
<thead>
<tr>
<th>method</th>
<th align="center">IN-1K</th>
<th align="center">IN-A</th>
<th align="center">IN-R</th>
<th align="center">IN-V2</th>
<th align="center">IN-Sketch</th>
<th align="center">ObjectNet</th>
</tr>
</thead>
<tbody>
<tr>
<td>OpenCLIP-G</td>
<td align="center">80.1</td>
<td align="center">69.3</td>
<td align="center">92.1</td>
<td align="center">73.6</td>
<td align="center">68.9</td>
<td align="center">73.0</td>
</tr>
<tr>
<td>EVA-02-CLIP-E+</td>
<td align="center">82.0</td>
<td align="center">82.1</td>
<td align="center">94.5</td>
<td align="center">75.7</td>
<td align="center">71.6</td>
<td align="center">79.6</td>
</tr>
<tr>
<td>ViT-22B*</td>
<td align="center">85.9</td>
<td align="center">90.1</td>
<td align="center">96.0</td>
<td align="center">80.9</td>
<td align="center">−</td>
<td align="center">87.6</td>
</tr>
<tr>
<td>InternVL-C (ours)</td>
<td align="center">83.2</td>
<td align="center">83.8</td>
<td align="center">95.5</td>
<td align="center">77.3</td>
<td align="center">73.9</td>
<td align="center">80.6</td>
</tr>
</tbody>
</table>
</li>
<li>
<p dir="auto">Multilingual Zero-Shot Image Classification <a href="/OpenGVLab/InternVL/blob/main/clip_benchmark#multilingual-imagenet-1k">[see details]</a></p>
<p dir="auto">EN: English, ZH: Chinese, JP: Japanese, Ar: Arabic, IT: Italian</p>
<table>
<thead>
<tr>
<th>method</th>
<th align="center">IN-1K (EN)</th>
<th align="center">IN-1K (ZH)</th>
<th align="center">IN-1K (JP)</th>
<th align="center">IN-1K (AR)</th>
<th align="center">IN-1K (IT)</th>
</tr>
</thead>
<tbody>
<tr>
<td>Taiyi-CLIP-ViT-H</td>
<td align="center">-</td>
<td align="center">54.4</td>
<td align="center">-</td>
<td align="center">-</td>
<td align="center">-</td>
</tr>
<tr>
<td>WuKong-ViT-L-G</td>
<td align="center">-</td>
<td align="center">57.5</td>
<td align="center">-</td>
<td align="center">-</td>
<td align="center">-</td>
</tr>
<tr>
<td>CN-CLIP-ViT-H</td>
<td align="center">-</td>
<td align="center">59.6</td>
<td align="center">-</td>
<td align="center">-</td>
<td align="center">-</td>
</tr>
<tr>
<td>AltCLIP-ViT-L</td>
<td align="center">74.5</td>
<td align="center">59.6</td>
<td align="center">-</td>
<td align="center">-</td>
<td align="center">-</td>
</tr>
<tr>
<td>EVA-02-CLIP-E+</td>
<td align="center">82.0</td>
<td align="center">-</td>
<td align="center">-</td>
<td align="center">-</td>
<td align="center">41.2</td>
</tr>
<tr>
<td>OpenCLIP-XLM-R-H</td>
<td align="center">77.0</td>
<td align="center">55.7</td>
<td align="center">53.1</td>
<td align="center">37.0</td>
<td align="center">56.8</td>
</tr>
<tr>
<td>InternVL-C (ours)</td>
<td align="center">83.2</td>
<td align="center">64.5</td>
<td align="center">61.5</td>
<td align="center">44.9</td>
<td align="center">65.7</td>
</tr>
</tbody>
</table>
</li>
<li>
<p dir="auto">Zero-Shot Video Classification [see details]</p>
<table>
<thead>
<tr>
<th>method</th>
<th align="center">#frame</th>
<th align="center">K400</th>
<th align="center">K600</th>
<th align="center">K700</th>
</tr>
</thead>
<tbody>
<tr>
<td>OpenCLIP-G</td>
<td align="center">1</td>
<td align="center">65.9</td>
<td align="center">66.1</td>
<td align="center">59.2</td>
</tr>
<tr>
<td>EVA-02-CLIP-E+</td>
<td align="center">1</td>
<td align="center">69.8</td>
<td align="center">69.3</td>
<td align="center">63.4</td>
</tr>
<tr>
<td>InternVL-C (ours)</td>
<td align="center">1</td>
<td align="center">71.0</td>
<td align="center">71.3</td>
<td align="center">65.7</td>
</tr>
<tr>
<td>ViCLIP</td>
<td align="center">8</td>
<td align="center">75.7</td>
<td align="center">73.5</td>
<td align="center">66.4</td>
</tr>
<tr>
<td>InternVL-C (ours)</td>
<td align="center">8</td>
<td align="center">79.4</td>
<td align="center">78.8</td>
<td align="center">71.5</td>
</tr>
</tbody>
</table>
</li>
</ul>
</details>
<details>
  <summary><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">跨模态检索（点击展开）</font></font></summary>
<ul dir="auto">
<li>
<p dir="auto">English Zero-Shot Image-Text Retrieval <a href="/OpenGVLab/InternVL/blob/main/clip_benchmark#flickr30k--coco">[see details]</a></p>
<table>
  <tbody><tr align="center">
      <td rowspan="3" align="left"><b>model</b></td>
      <td colspan="6" align="center"><b>Flickr30K</b></td>
      <td colspan="6" align="center"><b>COCO</b></td>
      <td rowspan="3" align="center"><b>avg</b></td>
</tr>
   <tr align="center">
      <td colspan="3" align="center"><b>image-to-text</b></td>
      <td colspan="3" align="center"><b>text-to-image</b></td>
       <td colspan="3" align="center"><b>image-to-text</b></td>
      <td colspan="3" align="center"><b>text-to-image</b></td>
   </tr>
   <tr>
      <td>R@1</td>
      <td>R@5</td>
      <td>R@10</td>
      <td>R@1</td>
      <td>R@5</td>
      <td>R@10</td>
      <td>R@1</td>
      <td>R@5</td>
      <td>R@10</td>
      <td>R@1</td>
      <td>R@5</td>
      <td>R@10</td>
   </tr>
<tr align="center">
      <td align="left">OpenCLIP-G</td>
      <td>92.9</td>
      <td>99.3</td>
      <td>99.8</td>
      <td>79.5</td>
      <td>95.0</td>
      <td>97.1</td>
      <td>67.3</td>
      <td>86.9</td>
      <td>92.6</td>
      <td>51.4</td>
      <td>74.9</td>
      <td>83.0</td>
      <td>85.0</td>
   </tr>
<tr align="center">
      <td align="left">EVA-02-CLIP-E+</td>
      <td>93.9</td>
      <td>99.4</td>
      <td>99.8</td>
      <td>78.8</td>
      <td>94.2</td>
      <td>96.8</td>
      <td>68.8</td>
      <td>87.8</td>
      <td>92.8</td>
      <td>51.1</td>
      <td>75.0</td>
      <td>82.7</td>
      <td>85.1</td>
   </tr>
  <tr align="center">
      <td align="left">EVA-CLIP-8B</td>
      <td>95.6</td>
      <td>99.6</td>
      <td>99.9</td>
      <td>80.8</td>
      <td>95.5</td>
      <td>97.6</td>
      <td>70.3</td>
      <td>89.3</td>
      <td>93.9</td>
      <td>53.0</td>
      <td>76.0</td>
      <td>83.4</td>
      <td>86.2</td>
   </tr>
<tr align="center">
      <td align="left">InternVL-C (ours)</td>
      <td>94.7</td>
      <td>99.6</td>
      <td>99.9</td>
      <td>81.7</td>
      <td>96.0</td>
      <td>98.2</td>
      <td>70.6</td>
      <td>89.0</td>
      <td>93.5</td>
      <td>54.1</td>
      <td>77.3</td>
      <td>84.6</td>
      <td>86.6</td>
   </tr>
<tr align="center">
      <td align="left">InternVL-G (ours)</td>
      <td>95.7</td>
      <td>99.7</td>
      <td>99.9</td>
      <td>85.0</td>
      <td>97.0</td>
      <td>98.6</td>
      <td>74.9</td>
      <td>91.3</td>
      <td>95.2</td>
      <td>58.6</td>
      <td>81.3</td>
      <td>88.0</td>
      <td>88.8</td>
   </tr>
</tbody></table>
</li>
<li>
<p dir="auto">Chinese Zero-Shot Image-Text Retrieval <a href="/OpenGVLab/InternVL/blob/main/clip_benchmark#flickr30k-cn--coco-cn">[see details]</a></p>
<table>
  <tbody><tr align="center">
      <td rowspan="3" align="left"><b>model</b></td>
      <td colspan="6" align="center"><b>Flickr30K-CN</b></td>
      <td colspan="6" align="center"><b>COCO-CN</b></td>
      <td rowspan="3" align="center"><b>avg</b></td>
</tr>
   <tr align="center">
      <td colspan="3" align="center"><b>image-to-text</b></td>
      <td colspan="3" align="center"><b>text-to-image</b></td>
       <td colspan="3" align="center"><b>image-to-text</b></td>
      <td colspan="3" align="center"><b>text-to-image</b></td>
   </tr>
   <tr>
      <td>R@1</td>
      <td>R@5</td>
      <td>R@10</td>
      <td>R@1</td>
      <td>R@5</td>
      <td>R@10</td>
      <td>R@1</td>
      <td>R@5</td>
      <td>R@10</td>
      <td>R@1</td>
      <td>R@5</td>
      <td>R@10</td>
   </tr>
<tr align="center">
      <td align="left">CN-CLIP-ViT-H</td>
      <td>81.6</td>
      <td>97.5</td>
      <td>98.8</td>
      <td>71.2</td>
      <td>91.4</td>
      <td>95.5</td>
      <td>63.0</td>
      <td>86.6</td>
      <td>92.9</td>
      <td>69.2</td>
      <td>89.9</td>
      <td>96.1</td>
      <td>86.1</td>
   </tr>
<tr align="center">
      <td align="left">OpenCLIP-XLM-R-H</td>
      <td>86.1</td>
      <td>97.5</td>
      <td>99.2</td>
      <td>71.0</td>
      <td>90.5</td>
      <td>94.9</td>
      <td>70.0</td>
      <td>91.5</td>
      <td>97.0</td>
      <td>66.1</td>
      <td>90.8</td>
      <td>96.0</td>
      <td>87.6</td>
   </tr>
<tr align="center">
      <td align="left">InternVL-C (ours)</td>
      <td>90.3</td>
      <td>98.8</td>
      <td>99.7</td>
      <td>75.1</td>
      <td>92.9</td>
      <td>96.4</td>
      <td>68.8</td>
      <td>92.0</td>
      <td>96.7</td>
      <td>68.9</td>
      <td>91.9</td>
      <td>96.5</td>
      <td>89.0</td>
   </tr>
<tr align="center">
      <td align="left">InternVL-G (ours)</td>
      <td>92.9</td>
      <td>99.4</td>
      <td>99.8</td>
      <td>77.7</td>
      <td>94.8</td>
      <td>97.3</td>
      <td>71.4</td>
      <td>93.9</td>
      <td>97.7</td>
      <td>73.8</td>
      <td>94.4</td>
      <td>98.1</td>
      <td>90.9</td>
   </tr>
</tbody></table>
</li>
<li>
<p dir="auto">Multilingual Zero-Shot Image-Text Retrieval on XTD <a href="/OpenGVLab/InternVL/blob/main/clip_benchmark#xtd">[see details]</a></p>
<table>
<thead>
<tr>
<th>method</th>
<th align="center">EN</th>
<th align="center">ES</th>
<th align="center">FR</th>
<th align="center">ZH</th>
<th align="center">IT</th>
<th align="center">KO</th>
<th align="center">RU</th>
<th align="center">JP</th>
<th align="center">average</th>
</tr>
</thead>
<tbody>
<tr>
<td>AltCLIP</td>
<td align="center">95.4</td>
<td align="center">94.1</td>
<td align="center">92.9</td>
<td align="center">95.1</td>
<td align="center">94.2</td>
<td align="center">94.4</td>
<td align="center">91.8</td>
<td align="center">91.7</td>
<td align="center">93.7</td>
</tr>
<tr>
<td>OpenCLIP-XLM-R-H</td>
<td align="center">97.3</td>
<td align="center">96.1</td>
<td align="center">94.5</td>
<td align="center">94.7</td>
<td align="center">96.0</td>
<td align="center">90.2</td>
<td align="center">93.9</td>
<td align="center">94.0</td>
<td align="center">94.6</td>
</tr>
<tr>
<td>InternVL-C (ours)</td>
<td align="center">97.3</td>
<td align="center">95.7</td>
<td align="center">95.1</td>
<td align="center">95.6</td>
<td align="center">96.0</td>
<td align="center">92.2</td>
<td align="center">93.3</td>
<td align="center">95.5</td>
<td align="center">95.1</td>
</tr>
<tr>
<td>InternVL-G (ours)</td>
<td align="center">98.6</td>
<td align="center">97.7</td>
<td align="center">96.5</td>
<td align="center">96.7</td>
<td align="center">96.9</td>
<td align="center">95.1</td>
<td align="center">94.8</td>
<td align="center">96.1</td>
<td align="center">96.6</td>
</tr>
</tbody>
</table>
</li>
</ul>
</details>
<details>
  <summary><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">多模态对话（参见“与 SOTA VLLM 的比较”）</font></font></summary>
</details>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Huggingface 快速启动</font></font></h2><a id="user-content-quick-start-with-huggingface" class="anchor" aria-label="永久链接：Huggingface 快速入门" href="#quick-start-with-huggingface"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<details>
  <summary><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 InternViT-6B（点击展开）</font></font></summary>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">import</span> <span class="pl-s1">torch</span>
<span class="pl-k">from</span> <span class="pl-v">PIL</span> <span class="pl-k">import</span> <span class="pl-v">Image</span>
<span class="pl-k">from</span> <span class="pl-s1">transformers</span> <span class="pl-k">import</span> <span class="pl-v">AutoModel</span>, <span class="pl-v">CLIPImageProcessor</span>

<span class="pl-s1">model</span> <span class="pl-c1">=</span> <span class="pl-v">AutoModel</span>.<span class="pl-en">from_pretrained</span>(
    <span class="pl-s">'OpenGVLab/InternViT-6B-224px'</span>,
    <span class="pl-s1">torch_dtype</span><span class="pl-c1">=</span><span class="pl-s1">torch</span>.<span class="pl-s1">bfloat16</span>,
    <span class="pl-s1">low_cpu_mem_usage</span><span class="pl-c1">=</span><span class="pl-c1">True</span>,
    <span class="pl-s1">trust_remote_code</span><span class="pl-c1">=</span><span class="pl-c1">True</span>).<span class="pl-en">cuda</span>().<span class="pl-en">eval</span>()

<span class="pl-s1">image</span> <span class="pl-c1">=</span> <span class="pl-v">Image</span>.<span class="pl-en">open</span>(<span class="pl-s">'./examples/image1.jpg'</span>).<span class="pl-en">convert</span>(<span class="pl-s">'RGB'</span>)

<span class="pl-s1">image_processor</span> <span class="pl-c1">=</span> <span class="pl-v">CLIPImageProcessor</span>.<span class="pl-en">from_pretrained</span>(<span class="pl-s">'OpenGVLab/InternViT-6B-224px'</span>)

<span class="pl-s1">pixel_values</span> <span class="pl-c1">=</span> <span class="pl-en">image_processor</span>(<span class="pl-s1">images</span><span class="pl-c1">=</span><span class="pl-s1">image</span>, <span class="pl-s1">return_tensors</span><span class="pl-c1">=</span><span class="pl-s">'pt'</span>).<span class="pl-s1">pixel_values</span>
<span class="pl-s1">pixel_values</span> <span class="pl-c1">=</span> <span class="pl-s1">pixel_values</span>.<span class="pl-en">to</span>(<span class="pl-s1">torch</span>.<span class="pl-s1">bfloat16</span>).<span class="pl-en">cuda</span>()

<span class="pl-s1">outputs</span> <span class="pl-c1">=</span> <span class="pl-en">model</span>(<span class="pl-s1">pixel_values</span>)</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="import torch
from PIL import Image
from transformers import AutoModel, CLIPImageProcessor

model = AutoModel.from_pretrained(
    'OpenGVLab/InternViT-6B-224px',
    torch_dtype=torch.bfloat16,
    low_cpu_mem_usage=True,
    trust_remote_code=True).cuda().eval()

image = Image.open('./examples/image1.jpg').convert('RGB')

image_processor = CLIPImageProcessor.from_pretrained('OpenGVLab/InternViT-6B-224px')

pixel_values = image_processor(images=image, return_tensors='pt').pixel_values
pixel_values = pixel_values.to(torch.bfloat16).cuda()

outputs = model(pixel_values)" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</details>
<details>
  <summary><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 InternVL-C（对比）和 InternVL-G（生成）（点击展开）</font></font></summary>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">import</span> <span class="pl-s1">torch</span>
<span class="pl-k">from</span> <span class="pl-v">PIL</span> <span class="pl-k">import</span> <span class="pl-v">Image</span>
<span class="pl-k">from</span> <span class="pl-s1">transformers</span> <span class="pl-k">import</span> <span class="pl-v">AutoModel</span>, <span class="pl-v">CLIPImageProcessor</span>
<span class="pl-k">from</span> <span class="pl-s1">transformers</span> <span class="pl-k">import</span> <span class="pl-v">AutoTokenizer</span>


<span class="pl-s1">model</span> <span class="pl-c1">=</span> <span class="pl-v">AutoModel</span>.<span class="pl-en">from_pretrained</span>(
    <span class="pl-s">'OpenGVLab/InternVL-14B-224px'</span>,
    <span class="pl-s1">torch_dtype</span><span class="pl-c1">=</span><span class="pl-s1">torch</span>.<span class="pl-s1">bfloat16</span>,
    <span class="pl-s1">low_cpu_mem_usage</span><span class="pl-c1">=</span><span class="pl-c1">True</span>,
    <span class="pl-s1">trust_remote_code</span><span class="pl-c1">=</span><span class="pl-c1">True</span>).<span class="pl-en">cuda</span>().<span class="pl-en">eval</span>()

<span class="pl-s1">image_processor</span> <span class="pl-c1">=</span> <span class="pl-v">CLIPImageProcessor</span>.<span class="pl-en">from_pretrained</span>(<span class="pl-s">'OpenGVLab/InternVL-14B-224px'</span>)

<span class="pl-s1">tokenizer</span> <span class="pl-c1">=</span> <span class="pl-v">AutoTokenizer</span>.<span class="pl-en">from_pretrained</span>(
    <span class="pl-s">'OpenGVLab/InternVL-14B-224px'</span>, <span class="pl-s1">use_fast</span><span class="pl-c1">=</span><span class="pl-c1">False</span>, <span class="pl-s1">add_eos_token</span><span class="pl-c1">=</span><span class="pl-c1">True</span>)
<span class="pl-s1">tokenizer</span>.<span class="pl-s1">pad_token_id</span> <span class="pl-c1">=</span> <span class="pl-c1">0</span>  <span class="pl-c"># set pad_token_id to 0</span>

<span class="pl-s1">images</span> <span class="pl-c1">=</span> [
    <span class="pl-v">Image</span>.<span class="pl-en">open</span>(<span class="pl-s">'./examples/image1.jpg'</span>).<span class="pl-en">convert</span>(<span class="pl-s">'RGB'</span>),
    <span class="pl-v">Image</span>.<span class="pl-en">open</span>(<span class="pl-s">'./examples/image2.jpg'</span>).<span class="pl-en">convert</span>(<span class="pl-s">'RGB'</span>),
    <span class="pl-v">Image</span>.<span class="pl-en">open</span>(<span class="pl-s">'./examples/image3.jpg'</span>).<span class="pl-en">convert</span>(<span class="pl-s">'RGB'</span>)
]
<span class="pl-s1">prefix</span> <span class="pl-c1">=</span> <span class="pl-s">'summarize:'</span>
<span class="pl-s1">texts</span> <span class="pl-c1">=</span> [
    <span class="pl-s1">prefix</span> <span class="pl-c1">+</span> <span class="pl-s">'a photo of a red panda'</span>,  <span class="pl-c"># English</span>
    <span class="pl-s1">prefix</span> <span class="pl-c1">+</span> <span class="pl-s">'一张熊猫的照片'</span>,  <span class="pl-c"># Chinese</span>
    <span class="pl-s1">prefix</span> <span class="pl-c1">+</span> <span class="pl-s">'二匹の猫の写真'</span>  <span class="pl-c"># Japanese</span>
]

<span class="pl-s1">pixel_values</span> <span class="pl-c1">=</span> <span class="pl-en">image_processor</span>(<span class="pl-s1">images</span><span class="pl-c1">=</span><span class="pl-s1">images</span>, <span class="pl-s1">return_tensors</span><span class="pl-c1">=</span><span class="pl-s">'pt'</span>).<span class="pl-s1">pixel_values</span>
<span class="pl-s1">pixel_values</span> <span class="pl-c1">=</span> <span class="pl-s1">pixel_values</span>.<span class="pl-en">to</span>(<span class="pl-s1">torch</span>.<span class="pl-s1">bfloat16</span>).<span class="pl-en">cuda</span>()
<span class="pl-s1">input_ids</span> <span class="pl-c1">=</span> <span class="pl-en">tokenizer</span>(<span class="pl-s1">texts</span>, <span class="pl-s1">return_tensors</span><span class="pl-c1">=</span><span class="pl-s">'pt'</span>, <span class="pl-s1">max_length</span><span class="pl-c1">=</span><span class="pl-c1">80</span>,
                      <span class="pl-s1">truncation</span><span class="pl-c1">=</span><span class="pl-c1">True</span>, <span class="pl-s1">padding</span><span class="pl-c1">=</span><span class="pl-s">'max_length'</span>).<span class="pl-s1">input_ids</span>.<span class="pl-en">cuda</span>()

<span class="pl-c"># InternVL-C</span>
<span class="pl-s1">logits_per_image</span>, <span class="pl-s1">logits_per_text</span> <span class="pl-c1">=</span> <span class="pl-en">model</span>(
    <span class="pl-s1">image</span><span class="pl-c1">=</span><span class="pl-s1">pixel_values</span>, <span class="pl-s1">text</span><span class="pl-c1">=</span><span class="pl-s1">input_ids</span>, <span class="pl-s1">mode</span><span class="pl-c1">=</span><span class="pl-s">'InternVL-C'</span>)
<span class="pl-s1">probs</span> <span class="pl-c1">=</span> <span class="pl-s1">logits_per_image</span>.<span class="pl-en">softmax</span>(<span class="pl-s1">dim</span><span class="pl-c1">=</span><span class="pl-c1">-</span><span class="pl-c1">1</span>)
<span class="pl-c"># tensor([[9.9609e-01, 5.2185e-03, 6.0070e-08],</span>
<span class="pl-c">#         [2.2949e-02, 9.7656e-01, 5.9903e-06],</span>
<span class="pl-c">#         [3.2932e-06, 7.4863e-05, 1.0000e+00]], device='cuda:0',</span>
<span class="pl-c">#        dtype=torch.bfloat16, grad_fn=&lt;SoftmaxBackward0&gt;)</span>

<span class="pl-c"># InternVL-G</span>
<span class="pl-s1">logits_per_image</span>, <span class="pl-s1">logits_per_text</span> <span class="pl-c1">=</span> <span class="pl-en">model</span>(
    <span class="pl-s1">image</span><span class="pl-c1">=</span><span class="pl-s1">pixel_values</span>, <span class="pl-s1">text</span><span class="pl-c1">=</span><span class="pl-s1">input_ids</span>, <span class="pl-s1">mode</span><span class="pl-c1">=</span><span class="pl-s">'InternVL-G'</span>)
<span class="pl-s1">probs</span> <span class="pl-c1">=</span> <span class="pl-s1">logits_per_image</span>.<span class="pl-en">softmax</span>(<span class="pl-s1">dim</span><span class="pl-c1">=</span><span class="pl-c1">-</span><span class="pl-c1">1</span>)
<span class="pl-c"># tensor([[9.9609e-01, 3.1738e-03, 3.6322e-08],</span>
<span class="pl-c">#         [8.6060e-03, 9.9219e-01, 2.8759e-06],</span>
<span class="pl-c">#         [1.7583e-06, 3.1233e-05, 1.0000e+00]], device='cuda:0',</span>
<span class="pl-c">#        dtype=torch.bfloat16, grad_fn=&lt;SoftmaxBackward0&gt;)</span>

<span class="pl-c"># please set add_eos_token to False for generation</span>
<span class="pl-s1">tokenizer</span>.<span class="pl-s1">add_eos_token</span> <span class="pl-c1">=</span> <span class="pl-c1">False</span>
<span class="pl-s1">image</span> <span class="pl-c1">=</span> <span class="pl-v">Image</span>.<span class="pl-en">open</span>(<span class="pl-s">'./examples/image1.jpg'</span>).<span class="pl-en">convert</span>(<span class="pl-s">'RGB'</span>)
<span class="pl-s1">pixel_values</span> <span class="pl-c1">=</span> <span class="pl-en">image_processor</span>(<span class="pl-s1">images</span><span class="pl-c1">=</span><span class="pl-s1">image</span>, <span class="pl-s1">return_tensors</span><span class="pl-c1">=</span><span class="pl-s">'pt'</span>).<span class="pl-s1">pixel_values</span>
<span class="pl-s1">pixel_values</span> <span class="pl-c1">=</span> <span class="pl-s1">pixel_values</span>.<span class="pl-en">to</span>(<span class="pl-s1">torch</span>.<span class="pl-s1">bfloat16</span>).<span class="pl-en">cuda</span>()

<span class="pl-s1">tokenized</span> <span class="pl-c1">=</span> <span class="pl-en">tokenizer</span>(<span class="pl-s">"English caption:"</span>, <span class="pl-s1">return_tensors</span><span class="pl-c1">=</span><span class="pl-s">'pt'</span>)
<span class="pl-s1">pred</span> <span class="pl-c1">=</span> <span class="pl-s1">model</span>.<span class="pl-en">generate</span>(
    <span class="pl-s1">pixel_values</span><span class="pl-c1">=</span><span class="pl-s1">pixel_values</span>,
    <span class="pl-s1">input_ids</span><span class="pl-c1">=</span><span class="pl-s1">tokenized</span>.<span class="pl-s1">input_ids</span>.<span class="pl-en">cuda</span>(),
    <span class="pl-s1">attention_mask</span><span class="pl-c1">=</span><span class="pl-s1">tokenized</span>.<span class="pl-s1">attention_mask</span>.<span class="pl-en">cuda</span>(),
    <span class="pl-s1">num_beams</span><span class="pl-c1">=</span><span class="pl-c1">5</span>,
    <span class="pl-s1">min_new_tokens</span><span class="pl-c1">=</span><span class="pl-c1">8</span>,
)
<span class="pl-s1">caption</span> <span class="pl-c1">=</span> <span class="pl-s1">tokenizer</span>.<span class="pl-en">decode</span>(<span class="pl-s1">pred</span>[<span class="pl-c1">0</span>].<span class="pl-en">cpu</span>(), <span class="pl-s1">skip_special_tokens</span><span class="pl-c1">=</span><span class="pl-c1">True</span>).<span class="pl-en">strip</span>()
<span class="pl-c"># English caption: a red panda sitting on top of a wooden platform</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="import torch
from PIL import Image
from transformers import AutoModel, CLIPImageProcessor
from transformers import AutoTokenizer


model = AutoModel.from_pretrained(
    'OpenGVLab/InternVL-14B-224px',
    torch_dtype=torch.bfloat16,
    low_cpu_mem_usage=True,
    trust_remote_code=True).cuda().eval()

image_processor = CLIPImageProcessor.from_pretrained('OpenGVLab/InternVL-14B-224px')

tokenizer = AutoTokenizer.from_pretrained(
    'OpenGVLab/InternVL-14B-224px', use_fast=False, add_eos_token=True)
tokenizer.pad_token_id = 0  # set pad_token_id to 0

images = [
    Image.open('./examples/image1.jpg').convert('RGB'),
    Image.open('./examples/image2.jpg').convert('RGB'),
    Image.open('./examples/image3.jpg').convert('RGB')
]
prefix = 'summarize:'
texts = [
    prefix + 'a photo of a red panda',  # English
    prefix + '一张熊猫的照片',  # Chinese
    prefix + '二匹の猫の写真'  # Japanese
]

pixel_values = image_processor(images=images, return_tensors='pt').pixel_values
pixel_values = pixel_values.to(torch.bfloat16).cuda()
input_ids = tokenizer(texts, return_tensors='pt', max_length=80,
                      truncation=True, padding='max_length').input_ids.cuda()

# InternVL-C
logits_per_image, logits_per_text = model(
    image=pixel_values, text=input_ids, mode='InternVL-C')
probs = logits_per_image.softmax(dim=-1)
# tensor([[9.9609e-01, 5.2185e-03, 6.0070e-08],
#         [2.2949e-02, 9.7656e-01, 5.9903e-06],
#         [3.2932e-06, 7.4863e-05, 1.0000e+00]], device='cuda:0',
#        dtype=torch.bfloat16, grad_fn=<SoftmaxBackward0>)

# InternVL-G
logits_per_image, logits_per_text = model(
    image=pixel_values, text=input_ids, mode='InternVL-G')
probs = logits_per_image.softmax(dim=-1)
# tensor([[9.9609e-01, 3.1738e-03, 3.6322e-08],
#         [8.6060e-03, 9.9219e-01, 2.8759e-06],
#         [1.7583e-06, 3.1233e-05, 1.0000e+00]], device='cuda:0',
#        dtype=torch.bfloat16, grad_fn=<SoftmaxBackward0>)

# please set add_eos_token to False for generation
tokenizer.add_eos_token = False
image = Image.open('./examples/image1.jpg').convert('RGB')
pixel_values = image_processor(images=image, return_tensors='pt').pixel_values
pixel_values = pixel_values.to(torch.bfloat16).cuda()

tokenized = tokenizer(&quot;English caption:&quot;, return_tensors='pt')
pred = model.generate(
    pixel_values=pixel_values,
    input_ids=tokenized.input_ids.cuda(),
    attention_mask=tokenized.attention_mask.cuda(),
    num_beams=5,
    min_new_tokens=8,
)
caption = tokenizer.decode(pred[0].cpu(), skip_special_tokens=True).strip()
# English caption: a red panda sitting on top of a wooden platform" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</details>
<details>
  <summary><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 InternVL-Chat（点击展开）</font></font></summary>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">from</span> <span class="pl-s1">transformers</span> <span class="pl-k">import</span> <span class="pl-v">AutoTokenizer</span>, <span class="pl-v">AutoModel</span>
<span class="pl-k">import</span> <span class="pl-s1">torch</span>
<span class="pl-k">import</span> <span class="pl-s1">torchvision</span>.<span class="pl-s1">transforms</span> <span class="pl-k">as</span> <span class="pl-v">T</span>
<span class="pl-k">from</span> <span class="pl-v">PIL</span> <span class="pl-k">import</span> <span class="pl-v">Image</span>

<span class="pl-k">from</span> <span class="pl-s1">torchvision</span>.<span class="pl-s1">transforms</span>.<span class="pl-s1">functional</span> <span class="pl-k">import</span> <span class="pl-v">InterpolationMode</span>


<span class="pl-v">IMAGENET_MEAN</span> <span class="pl-c1">=</span> (<span class="pl-c1">0.485</span>, <span class="pl-c1">0.456</span>, <span class="pl-c1">0.406</span>)
<span class="pl-v">IMAGENET_STD</span> <span class="pl-c1">=</span> (<span class="pl-c1">0.229</span>, <span class="pl-c1">0.224</span>, <span class="pl-c1">0.225</span>)


<span class="pl-k">def</span> <span class="pl-en">build_transform</span>(<span class="pl-s1">input_size</span>):
    <span class="pl-v">MEAN</span>, <span class="pl-v">STD</span> <span class="pl-c1">=</span> <span class="pl-v">IMAGENET_MEAN</span>, <span class="pl-v">IMAGENET_STD</span>
    <span class="pl-s1">transform</span> <span class="pl-c1">=</span> <span class="pl-v">T</span>.<span class="pl-v">Compose</span>([
        <span class="pl-v">T</span>.<span class="pl-v">Lambda</span>(<span class="pl-k">lambda</span> <span class="pl-s1">img</span>: <span class="pl-s1">img</span>.<span class="pl-en">convert</span>(<span class="pl-s">'RGB'</span>) <span class="pl-k">if</span> <span class="pl-s1">img</span>.<span class="pl-s1">mode</span> <span class="pl-c1">!=</span> <span class="pl-s">'RGB'</span> <span class="pl-k">else</span> <span class="pl-s1">img</span>),
        <span class="pl-v">T</span>.<span class="pl-v">Resize</span>((<span class="pl-s1">input_size</span>, <span class="pl-s1">input_size</span>), <span class="pl-s1">interpolation</span><span class="pl-c1">=</span><span class="pl-v">InterpolationMode</span>.<span class="pl-v">BICUBIC</span>),
        <span class="pl-v">T</span>.<span class="pl-v">ToTensor</span>(),
        <span class="pl-v">T</span>.<span class="pl-v">Normalize</span>(<span class="pl-s1">mean</span><span class="pl-c1">=</span><span class="pl-v">MEAN</span>, <span class="pl-s1">std</span><span class="pl-c1">=</span><span class="pl-v">STD</span>)
    ])
    <span class="pl-k">return</span> <span class="pl-s1">transform</span>


<span class="pl-k">def</span> <span class="pl-en">find_closest_aspect_ratio</span>(<span class="pl-s1">aspect_ratio</span>, <span class="pl-s1">target_ratios</span>, <span class="pl-s1">width</span>, <span class="pl-s1">height</span>, <span class="pl-s1">image_size</span>):
    <span class="pl-s1">best_ratio_diff</span> <span class="pl-c1">=</span> <span class="pl-en">float</span>(<span class="pl-s">'inf'</span>)
    <span class="pl-s1">best_ratio</span> <span class="pl-c1">=</span> (<span class="pl-c1">1</span>, <span class="pl-c1">1</span>)
    <span class="pl-s1">area</span> <span class="pl-c1">=</span> <span class="pl-s1">width</span> <span class="pl-c1">*</span> <span class="pl-s1">height</span>
    <span class="pl-k">for</span> <span class="pl-s1">ratio</span> <span class="pl-c1">in</span> <span class="pl-s1">target_ratios</span>:
        <span class="pl-s1">target_aspect_ratio</span> <span class="pl-c1">=</span> <span class="pl-s1">ratio</span>[<span class="pl-c1">0</span>] <span class="pl-c1">/</span> <span class="pl-s1">ratio</span>[<span class="pl-c1">1</span>]
        <span class="pl-s1">ratio_diff</span> <span class="pl-c1">=</span> <span class="pl-en">abs</span>(<span class="pl-s1">aspect_ratio</span> <span class="pl-c1">-</span> <span class="pl-s1">target_aspect_ratio</span>)
        <span class="pl-k">if</span> <span class="pl-s1">ratio_diff</span> <span class="pl-c1">&lt;</span> <span class="pl-s1">best_ratio_diff</span>:
            <span class="pl-s1">best_ratio_diff</span> <span class="pl-c1">=</span> <span class="pl-s1">ratio_diff</span>
            <span class="pl-s1">best_ratio</span> <span class="pl-c1">=</span> <span class="pl-s1">ratio</span>
        <span class="pl-k">elif</span> <span class="pl-s1">ratio_diff</span> <span class="pl-c1">==</span> <span class="pl-s1">best_ratio_diff</span>:
            <span class="pl-k">if</span> <span class="pl-s1">area</span> <span class="pl-c1">&gt;</span> <span class="pl-c1">0.5</span> <span class="pl-c1">*</span> <span class="pl-s1">image_size</span> <span class="pl-c1">*</span> <span class="pl-s1">image_size</span> <span class="pl-c1">*</span> <span class="pl-s1">ratio</span>[<span class="pl-c1">0</span>] <span class="pl-c1">*</span> <span class="pl-s1">ratio</span>[<span class="pl-c1">1</span>]:
                <span class="pl-s1">best_ratio</span> <span class="pl-c1">=</span> <span class="pl-s1">ratio</span>
    <span class="pl-k">return</span> <span class="pl-s1">best_ratio</span>


<span class="pl-k">def</span> <span class="pl-en">dynamic_preprocess</span>(<span class="pl-s1">image</span>, <span class="pl-s1">min_num</span><span class="pl-c1">=</span><span class="pl-c1">1</span>, <span class="pl-s1">max_num</span><span class="pl-c1">=</span><span class="pl-c1">6</span>, <span class="pl-s1">image_size</span><span class="pl-c1">=</span><span class="pl-c1">448</span>, <span class="pl-s1">use_thumbnail</span><span class="pl-c1">=</span><span class="pl-c1">False</span>):
    <span class="pl-s1">orig_width</span>, <span class="pl-s1">orig_height</span> <span class="pl-c1">=</span> <span class="pl-s1">image</span>.<span class="pl-s1">size</span>
    <span class="pl-s1">aspect_ratio</span> <span class="pl-c1">=</span> <span class="pl-s1">orig_width</span> <span class="pl-c1">/</span> <span class="pl-s1">orig_height</span>

    <span class="pl-c"># calculate the existing image aspect ratio</span>
    <span class="pl-s1">target_ratios</span> <span class="pl-c1">=</span> <span class="pl-en">set</span>(
        (<span class="pl-s1">i</span>, <span class="pl-s1">j</span>) <span class="pl-k">for</span> <span class="pl-s1">n</span> <span class="pl-c1">in</span> <span class="pl-en">range</span>(<span class="pl-s1">min_num</span>, <span class="pl-s1">max_num</span> <span class="pl-c1">+</span> <span class="pl-c1">1</span>) <span class="pl-k">for</span> <span class="pl-s1">i</span> <span class="pl-c1">in</span> <span class="pl-en">range</span>(<span class="pl-c1">1</span>, <span class="pl-s1">n</span> <span class="pl-c1">+</span> <span class="pl-c1">1</span>) <span class="pl-k">for</span> <span class="pl-s1">j</span> <span class="pl-c1">in</span> <span class="pl-en">range</span>(<span class="pl-c1">1</span>, <span class="pl-s1">n</span> <span class="pl-c1">+</span> <span class="pl-c1">1</span>) <span class="pl-k">if</span>
        <span class="pl-s1">i</span> <span class="pl-c1">*</span> <span class="pl-s1">j</span> <span class="pl-c1">&lt;=</span> <span class="pl-s1">max_num</span> <span class="pl-c1">and</span> <span class="pl-s1">i</span> <span class="pl-c1">*</span> <span class="pl-s1">j</span> <span class="pl-c1">&gt;=</span> <span class="pl-s1">min_num</span>)
    <span class="pl-s1">target_ratios</span> <span class="pl-c1">=</span> <span class="pl-en">sorted</span>(<span class="pl-s1">target_ratios</span>, <span class="pl-s1">key</span><span class="pl-c1">=</span><span class="pl-k">lambda</span> <span class="pl-s1">x</span>: <span class="pl-s1">x</span>[<span class="pl-c1">0</span>] <span class="pl-c1">*</span> <span class="pl-s1">x</span>[<span class="pl-c1">1</span>])

    <span class="pl-c"># find the closest aspect ratio to the target</span>
    <span class="pl-s1">target_aspect_ratio</span> <span class="pl-c1">=</span> <span class="pl-en">find_closest_aspect_ratio</span>(
        <span class="pl-s1">aspect_ratio</span>, <span class="pl-s1">target_ratios</span>, <span class="pl-s1">orig_width</span>, <span class="pl-s1">orig_height</span>, <span class="pl-s1">image_size</span>)

    <span class="pl-c"># calculate the target width and height</span>
    <span class="pl-s1">target_width</span> <span class="pl-c1">=</span> <span class="pl-s1">image_size</span> <span class="pl-c1">*</span> <span class="pl-s1">target_aspect_ratio</span>[<span class="pl-c1">0</span>]
    <span class="pl-s1">target_height</span> <span class="pl-c1">=</span> <span class="pl-s1">image_size</span> <span class="pl-c1">*</span> <span class="pl-s1">target_aspect_ratio</span>[<span class="pl-c1">1</span>]
    <span class="pl-s1">blocks</span> <span class="pl-c1">=</span> <span class="pl-s1">target_aspect_ratio</span>[<span class="pl-c1">0</span>] <span class="pl-c1">*</span> <span class="pl-s1">target_aspect_ratio</span>[<span class="pl-c1">1</span>]

    <span class="pl-c"># resize the image</span>
    <span class="pl-s1">resized_img</span> <span class="pl-c1">=</span> <span class="pl-s1">image</span>.<span class="pl-en">resize</span>((<span class="pl-s1">target_width</span>, <span class="pl-s1">target_height</span>))
    <span class="pl-s1">processed_images</span> <span class="pl-c1">=</span> []
    <span class="pl-k">for</span> <span class="pl-s1">i</span> <span class="pl-c1">in</span> <span class="pl-en">range</span>(<span class="pl-s1">blocks</span>):
        <span class="pl-s1">box</span> <span class="pl-c1">=</span> (
            (<span class="pl-s1">i</span> <span class="pl-c1">%</span> (<span class="pl-s1">target_width</span> <span class="pl-c1">//</span> <span class="pl-s1">image_size</span>)) <span class="pl-c1">*</span> <span class="pl-s1">image_size</span>,
            (<span class="pl-s1">i</span> <span class="pl-c1">//</span> (<span class="pl-s1">target_width</span> <span class="pl-c1">//</span> <span class="pl-s1">image_size</span>)) <span class="pl-c1">*</span> <span class="pl-s1">image_size</span>,
            ((<span class="pl-s1">i</span> <span class="pl-c1">%</span> (<span class="pl-s1">target_width</span> <span class="pl-c1">//</span> <span class="pl-s1">image_size</span>)) <span class="pl-c1">+</span> <span class="pl-c1">1</span>) <span class="pl-c1">*</span> <span class="pl-s1">image_size</span>,
            ((<span class="pl-s1">i</span> <span class="pl-c1">//</span> (<span class="pl-s1">target_width</span> <span class="pl-c1">//</span> <span class="pl-s1">image_size</span>)) <span class="pl-c1">+</span> <span class="pl-c1">1</span>) <span class="pl-c1">*</span> <span class="pl-s1">image_size</span>
        )
        <span class="pl-c"># split the image</span>
        <span class="pl-s1">split_img</span> <span class="pl-c1">=</span> <span class="pl-s1">resized_img</span>.<span class="pl-en">crop</span>(<span class="pl-s1">box</span>)
        <span class="pl-s1">processed_images</span>.<span class="pl-en">append</span>(<span class="pl-s1">split_img</span>)
    <span class="pl-k">assert</span> <span class="pl-en">len</span>(<span class="pl-s1">processed_images</span>) <span class="pl-c1">==</span> <span class="pl-s1">blocks</span>
    <span class="pl-k">if</span> <span class="pl-s1">use_thumbnail</span> <span class="pl-c1">and</span> <span class="pl-en">len</span>(<span class="pl-s1">processed_images</span>) <span class="pl-c1">!=</span> <span class="pl-c1">1</span>:
        <span class="pl-s1">thumbnail_img</span> <span class="pl-c1">=</span> <span class="pl-s1">image</span>.<span class="pl-en">resize</span>((<span class="pl-s1">image_size</span>, <span class="pl-s1">image_size</span>))
        <span class="pl-s1">processed_images</span>.<span class="pl-en">append</span>(<span class="pl-s1">thumbnail_img</span>)
    <span class="pl-k">return</span> <span class="pl-s1">processed_images</span>


<span class="pl-k">def</span> <span class="pl-en">load_image</span>(<span class="pl-s1">image_file</span>, <span class="pl-s1">input_size</span><span class="pl-c1">=</span><span class="pl-c1">448</span>, <span class="pl-s1">max_num</span><span class="pl-c1">=</span><span class="pl-c1">6</span>):
    <span class="pl-s1">image</span> <span class="pl-c1">=</span> <span class="pl-v">Image</span>.<span class="pl-en">open</span>(<span class="pl-s1">image_file</span>).<span class="pl-en">convert</span>(<span class="pl-s">'RGB'</span>)
    <span class="pl-s1">transform</span> <span class="pl-c1">=</span> <span class="pl-en">build_transform</span>(<span class="pl-s1">input_size</span><span class="pl-c1">=</span><span class="pl-s1">input_size</span>)
    <span class="pl-s1">images</span> <span class="pl-c1">=</span> <span class="pl-en">dynamic_preprocess</span>(<span class="pl-s1">image</span>, <span class="pl-s1">image_size</span><span class="pl-c1">=</span><span class="pl-s1">input_size</span>, <span class="pl-s1">use_thumbnail</span><span class="pl-c1">=</span><span class="pl-c1">True</span>, <span class="pl-s1">max_num</span><span class="pl-c1">=</span><span class="pl-s1">max_num</span>)
    <span class="pl-s1">pixel_values</span> <span class="pl-c1">=</span> [<span class="pl-en">transform</span>(<span class="pl-s1">image</span>) <span class="pl-k">for</span> <span class="pl-s1">image</span> <span class="pl-c1">in</span> <span class="pl-s1">images</span>]
    <span class="pl-s1">pixel_values</span> <span class="pl-c1">=</span> <span class="pl-s1">torch</span>.<span class="pl-en">stack</span>(<span class="pl-s1">pixel_values</span>)
    <span class="pl-k">return</span> <span class="pl-s1">pixel_values</span>


<span class="pl-s1">path</span> <span class="pl-c1">=</span> <span class="pl-s">"OpenGVLab/InternVL-Chat-V1-5"</span>
<span class="pl-c"># If you have an 80G A100 GPU, you can put the entire model on a single GPU.</span>
<span class="pl-s1">model</span> <span class="pl-c1">=</span> <span class="pl-v">AutoModel</span>.<span class="pl-en">from_pretrained</span>(
    <span class="pl-s1">path</span>,
    <span class="pl-s1">torch_dtype</span><span class="pl-c1">=</span><span class="pl-s1">torch</span>.<span class="pl-s1">bfloat16</span>,
    <span class="pl-s1">low_cpu_mem_usage</span><span class="pl-c1">=</span><span class="pl-c1">True</span>,
    <span class="pl-s1">trust_remote_code</span><span class="pl-c1">=</span><span class="pl-c1">True</span>).<span class="pl-en">eval</span>().<span class="pl-en">cuda</span>()
<span class="pl-c"># Otherwise, you need to set device_map='auto' to use multiple GPUs for inference.</span>
<span class="pl-c"># model = AutoModel.from_pretrained(</span>
<span class="pl-c">#     path,</span>
<span class="pl-c">#     torch_dtype=torch.bfloat16,</span>
<span class="pl-c">#     low_cpu_mem_usage=True,</span>
<span class="pl-c">#     trust_remote_code=True,</span>
<span class="pl-c">#     device_map='auto').eval()</span>

<span class="pl-s1">tokenizer</span> <span class="pl-c1">=</span> <span class="pl-v">AutoTokenizer</span>.<span class="pl-en">from_pretrained</span>(<span class="pl-s1">path</span>, <span class="pl-s1">trust_remote_code</span><span class="pl-c1">=</span><span class="pl-c1">True</span>)
<span class="pl-c"># set the max number of tiles in `max_num`</span>
<span class="pl-s1">pixel_values</span> <span class="pl-c1">=</span> <span class="pl-en">load_image</span>(<span class="pl-s">'./examples/image1.jpg'</span>, <span class="pl-s1">max_num</span><span class="pl-c1">=</span><span class="pl-c1">6</span>).<span class="pl-en">to</span>(<span class="pl-s1">torch</span>.<span class="pl-s1">bfloat16</span>).<span class="pl-en">cuda</span>()

<span class="pl-s1">generation_config</span> <span class="pl-c1">=</span> <span class="pl-en">dict</span>(
    <span class="pl-s1">num_beams</span><span class="pl-c1">=</span><span class="pl-c1">1</span>,
    <span class="pl-s1">max_new_tokens</span><span class="pl-c1">=</span><span class="pl-c1">512</span>,
    <span class="pl-s1">do_sample</span><span class="pl-c1">=</span><span class="pl-c1">False</span>,
)

<span class="pl-c"># single-round single-image conversation</span>
<span class="pl-s1">question</span> <span class="pl-c1">=</span> <span class="pl-s">"请详细描述图片"</span> <span class="pl-c"># Please describe the picture in detail</span>
<span class="pl-s1">response</span> <span class="pl-c1">=</span> <span class="pl-s1">model</span>.<span class="pl-en">chat</span>(<span class="pl-s1">tokenizer</span>, <span class="pl-s1">pixel_values</span>, <span class="pl-s1">question</span>, <span class="pl-s1">generation_config</span>)
<span class="pl-en">print</span>(<span class="pl-s1">question</span>, <span class="pl-s1">response</span>)

<span class="pl-c"># multi-round single-image conversation</span>
<span class="pl-s1">question</span> <span class="pl-c1">=</span> <span class="pl-s">"请详细描述图片"</span> <span class="pl-c"># Please describe the picture in detail</span>
<span class="pl-s1">response</span>, <span class="pl-s1">history</span> <span class="pl-c1">=</span> <span class="pl-s1">model</span>.<span class="pl-en">chat</span>(<span class="pl-s1">tokenizer</span>, <span class="pl-s1">pixel_values</span>, <span class="pl-s1">question</span>, <span class="pl-s1">generation_config</span>, <span class="pl-s1">history</span><span class="pl-c1">=</span><span class="pl-c1">None</span>, <span class="pl-s1">return_history</span><span class="pl-c1">=</span><span class="pl-c1">True</span>)
<span class="pl-en">print</span>(<span class="pl-s1">question</span>, <span class="pl-s1">response</span>)

<span class="pl-s1">question</span> <span class="pl-c1">=</span> <span class="pl-s">"请根据图片写一首诗"</span> <span class="pl-c"># Please write a poem according to the picture</span>
<span class="pl-s1">response</span>, <span class="pl-s1">history</span> <span class="pl-c1">=</span> <span class="pl-s1">model</span>.<span class="pl-en">chat</span>(<span class="pl-s1">tokenizer</span>, <span class="pl-s1">pixel_values</span>, <span class="pl-s1">question</span>, <span class="pl-s1">generation_config</span>, <span class="pl-s1">history</span><span class="pl-c1">=</span><span class="pl-s1">history</span>, <span class="pl-s1">return_history</span><span class="pl-c1">=</span><span class="pl-c1">True</span>)
<span class="pl-en">print</span>(<span class="pl-s1">question</span>, <span class="pl-s1">response</span>)

<span class="pl-c"># multi-round multi-image conversation</span>
<span class="pl-s1">pixel_values1</span> <span class="pl-c1">=</span> <span class="pl-en">load_image</span>(<span class="pl-s">'./examples/image1.jpg'</span>, <span class="pl-s1">max_num</span><span class="pl-c1">=</span><span class="pl-c1">6</span>).<span class="pl-en">to</span>(<span class="pl-s1">torch</span>.<span class="pl-s1">bfloat16</span>).<span class="pl-en">cuda</span>()
<span class="pl-s1">pixel_values2</span> <span class="pl-c1">=</span> <span class="pl-en">load_image</span>(<span class="pl-s">'./examples/image2.jpg'</span>, <span class="pl-s1">max_num</span><span class="pl-c1">=</span><span class="pl-c1">6</span>).<span class="pl-en">to</span>(<span class="pl-s1">torch</span>.<span class="pl-s1">bfloat16</span>).<span class="pl-en">cuda</span>()
<span class="pl-s1">pixel_values</span> <span class="pl-c1">=</span> <span class="pl-s1">torch</span>.<span class="pl-en">cat</span>((<span class="pl-s1">pixel_values1</span>, <span class="pl-s1">pixel_values2</span>), <span class="pl-s1">dim</span><span class="pl-c1">=</span><span class="pl-c1">0</span>)

<span class="pl-s1">question</span> <span class="pl-c1">=</span> <span class="pl-s">"详细描述这两张图片"</span> <span class="pl-c"># Describe the two pictures in detail</span>
<span class="pl-s1">response</span>, <span class="pl-s1">history</span> <span class="pl-c1">=</span> <span class="pl-s1">model</span>.<span class="pl-en">chat</span>(<span class="pl-s1">tokenizer</span>, <span class="pl-s1">pixel_values</span>, <span class="pl-s1">question</span>, <span class="pl-s1">generation_config</span>, <span class="pl-s1">history</span><span class="pl-c1">=</span><span class="pl-c1">None</span>, <span class="pl-s1">return_history</span><span class="pl-c1">=</span><span class="pl-c1">True</span>)
<span class="pl-en">print</span>(<span class="pl-s1">question</span>, <span class="pl-s1">response</span>)

<span class="pl-s1">question</span> <span class="pl-c1">=</span> <span class="pl-s">"这两张图片的相同点和区别分别是什么"</span> <span class="pl-c"># What are the similarities and differences between these two pictures</span>
<span class="pl-s1">response</span>, <span class="pl-s1">history</span> <span class="pl-c1">=</span> <span class="pl-s1">model</span>.<span class="pl-en">chat</span>(<span class="pl-s1">tokenizer</span>, <span class="pl-s1">pixel_values</span>, <span class="pl-s1">question</span>, <span class="pl-s1">generation_config</span>, <span class="pl-s1">history</span><span class="pl-c1">=</span><span class="pl-s1">history</span>, <span class="pl-s1">return_history</span><span class="pl-c1">=</span><span class="pl-c1">True</span>)
<span class="pl-en">print</span>(<span class="pl-s1">question</span>, <span class="pl-s1">response</span>)

<span class="pl-c"># batch inference (single image per sample)</span>
<span class="pl-s1">pixel_values1</span> <span class="pl-c1">=</span> <span class="pl-en">load_image</span>(<span class="pl-s">'./examples/image1.jpg'</span>, <span class="pl-s1">max_num</span><span class="pl-c1">=</span><span class="pl-c1">6</span>).<span class="pl-en">to</span>(<span class="pl-s1">torch</span>.<span class="pl-s1">bfloat16</span>).<span class="pl-en">cuda</span>()
<span class="pl-s1">pixel_values2</span> <span class="pl-c1">=</span> <span class="pl-en">load_image</span>(<span class="pl-s">'./examples/image2.jpg'</span>, <span class="pl-s1">max_num</span><span class="pl-c1">=</span><span class="pl-c1">6</span>).<span class="pl-en">to</span>(<span class="pl-s1">torch</span>.<span class="pl-s1">bfloat16</span>).<span class="pl-en">cuda</span>()
<span class="pl-s1">image_counts</span> <span class="pl-c1">=</span> [<span class="pl-s1">pixel_values1</span>.<span class="pl-en">size</span>(<span class="pl-c1">0</span>), <span class="pl-s1">pixel_values2</span>.<span class="pl-en">size</span>(<span class="pl-c1">0</span>)]
<span class="pl-s1">pixel_values</span> <span class="pl-c1">=</span> <span class="pl-s1">torch</span>.<span class="pl-en">cat</span>((<span class="pl-s1">pixel_values1</span>, <span class="pl-s1">pixel_values2</span>), <span class="pl-s1">dim</span><span class="pl-c1">=</span><span class="pl-c1">0</span>)

<span class="pl-s1">questions</span> <span class="pl-c1">=</span> [<span class="pl-s">"Describe the image in detail."</span>] <span class="pl-c1">*</span> <span class="pl-en">len</span>(<span class="pl-s1">image_counts</span>)
<span class="pl-s1">responses</span> <span class="pl-c1">=</span> <span class="pl-s1">model</span>.<span class="pl-en">batch_chat</span>(<span class="pl-s1">tokenizer</span>, <span class="pl-s1">pixel_values</span>,
                             <span class="pl-s1">image_counts</span><span class="pl-c1">=</span><span class="pl-s1">image_counts</span>,
                             <span class="pl-s1">questions</span><span class="pl-c1">=</span><span class="pl-s1">questions</span>,
                             <span class="pl-s1">generation_config</span><span class="pl-c1">=</span><span class="pl-s1">generation_config</span>)
<span class="pl-k">for</span> <span class="pl-s1">question</span>, <span class="pl-s1">response</span> <span class="pl-c1">in</span> <span class="pl-en">zip</span>(<span class="pl-s1">questions</span>, <span class="pl-s1">responses</span>):
    <span class="pl-en">print</span>(<span class="pl-s1">question</span>)
    <span class="pl-en">print</span>(<span class="pl-s1">response</span>)</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="from transformers import AutoTokenizer, AutoModel
import torch
import torchvision.transforms as T
from PIL import Image

from torchvision.transforms.functional import InterpolationMode


IMAGENET_MEAN = (0.485, 0.456, 0.406)
IMAGENET_STD = (0.229, 0.224, 0.225)


def build_transform(input_size):
    MEAN, STD = IMAGENET_MEAN, IMAGENET_STD
    transform = T.Compose([
        T.Lambda(lambda img: img.convert('RGB') if img.mode != 'RGB' else img),
        T.Resize((input_size, input_size), interpolation=InterpolationMode.BICUBIC),
        T.ToTensor(),
        T.Normalize(mean=MEAN, std=STD)
    ])
    return transform


def find_closest_aspect_ratio(aspect_ratio, target_ratios, width, height, image_size):
    best_ratio_diff = float('inf')
    best_ratio = (1, 1)
    area = width * height
    for ratio in target_ratios:
        target_aspect_ratio = ratio[0] / ratio[1]
        ratio_diff = abs(aspect_ratio - target_aspect_ratio)
        if ratio_diff < best_ratio_diff:
            best_ratio_diff = ratio_diff
            best_ratio = ratio
        elif ratio_diff == best_ratio_diff:
            if area > 0.5 * image_size * image_size * ratio[0] * ratio[1]:
                best_ratio = ratio
    return best_ratio


def dynamic_preprocess(image, min_num=1, max_num=6, image_size=448, use_thumbnail=False):
    orig_width, orig_height = image.size
    aspect_ratio = orig_width / orig_height

    # calculate the existing image aspect ratio
    target_ratios = set(
        (i, j) for n in range(min_num, max_num + 1) for i in range(1, n + 1) for j in range(1, n + 1) if
        i * j <= max_num and i * j >= min_num)
    target_ratios = sorted(target_ratios, key=lambda x: x[0] * x[1])

    # find the closest aspect ratio to the target
    target_aspect_ratio = find_closest_aspect_ratio(
        aspect_ratio, target_ratios, orig_width, orig_height, image_size)

    # calculate the target width and height
    target_width = image_size * target_aspect_ratio[0]
    target_height = image_size * target_aspect_ratio[1]
    blocks = target_aspect_ratio[0] * target_aspect_ratio[1]

    # resize the image
    resized_img = image.resize((target_width, target_height))
    processed_images = []
    for i in range(blocks):
        box = (
            (i % (target_width // image_size)) * image_size,
            (i // (target_width // image_size)) * image_size,
            ((i % (target_width // image_size)) + 1) * image_size,
            ((i // (target_width // image_size)) + 1) * image_size
        )
        # split the image
        split_img = resized_img.crop(box)
        processed_images.append(split_img)
    assert len(processed_images) == blocks
    if use_thumbnail and len(processed_images) != 1:
        thumbnail_img = image.resize((image_size, image_size))
        processed_images.append(thumbnail_img)
    return processed_images


def load_image(image_file, input_size=448, max_num=6):
    image = Image.open(image_file).convert('RGB')
    transform = build_transform(input_size=input_size)
    images = dynamic_preprocess(image, image_size=input_size, use_thumbnail=True, max_num=max_num)
    pixel_values = [transform(image) for image in images]
    pixel_values = torch.stack(pixel_values)
    return pixel_values


path = &quot;OpenGVLab/InternVL-Chat-V1-5&quot;
# If you have an 80G A100 GPU, you can put the entire model on a single GPU.
model = AutoModel.from_pretrained(
    path,
    torch_dtype=torch.bfloat16,
    low_cpu_mem_usage=True,
    trust_remote_code=True).eval().cuda()
# Otherwise, you need to set device_map='auto' to use multiple GPUs for inference.
# model = AutoModel.from_pretrained(
#     path,
#     torch_dtype=torch.bfloat16,
#     low_cpu_mem_usage=True,
#     trust_remote_code=True,
#     device_map='auto').eval()

tokenizer = AutoTokenizer.from_pretrained(path, trust_remote_code=True)
# set the max number of tiles in `max_num`
pixel_values = load_image('./examples/image1.jpg', max_num=6).to(torch.bfloat16).cuda()

generation_config = dict(
    num_beams=1,
    max_new_tokens=512,
    do_sample=False,
)

# single-round single-image conversation
question = &quot;请详细描述图片&quot; # Please describe the picture in detail
response = model.chat(tokenizer, pixel_values, question, generation_config)
print(question, response)

# multi-round single-image conversation
question = &quot;请详细描述图片&quot; # Please describe the picture in detail
response, history = model.chat(tokenizer, pixel_values, question, generation_config, history=None, return_history=True)
print(question, response)

question = &quot;请根据图片写一首诗&quot; # Please write a poem according to the picture
response, history = model.chat(tokenizer, pixel_values, question, generation_config, history=history, return_history=True)
print(question, response)

# multi-round multi-image conversation
pixel_values1 = load_image('./examples/image1.jpg', max_num=6).to(torch.bfloat16).cuda()
pixel_values2 = load_image('./examples/image2.jpg', max_num=6).to(torch.bfloat16).cuda()
pixel_values = torch.cat((pixel_values1, pixel_values2), dim=0)

question = &quot;详细描述这两张图片&quot; # Describe the two pictures in detail
response, history = model.chat(tokenizer, pixel_values, question, generation_config, history=None, return_history=True)
print(question, response)

question = &quot;这两张图片的相同点和区别分别是什么&quot; # What are the similarities and differences between these two pictures
response, history = model.chat(tokenizer, pixel_values, question, generation_config, history=history, return_history=True)
print(question, response)

# batch inference (single image per sample)
pixel_values1 = load_image('./examples/image1.jpg', max_num=6).to(torch.bfloat16).cuda()
pixel_values2 = load_image('./examples/image2.jpg', max_num=6).to(torch.bfloat16).cuda()
image_counts = [pixel_values1.size(0), pixel_values2.size(0)]
pixel_values = torch.cat((pixel_values1, pixel_values2), dim=0)

questions = [&quot;Describe the image in detail.&quot;] * len(image_counts)
responses = model.batch_chat(tokenizer, pixel_values,
                             image_counts=image_counts,
                             questions=questions,
                             generation_config=generation_config)
for question, response in zip(questions, responses):
    print(question)
    print(response)" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</details>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">执照</font></font></h2><a id="user-content-license" class="anchor" aria-label="永久链接：许可证" href="#license"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该项目是在</font></font><a href="/OpenGVLab/InternVL/blob/main/LICENSE"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MIT 许可</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下发布的。该项目的部分内容包含来自其他来源的代码和模型，这些代码和模型受各自的许可约束。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">引文</font></font></h2><a id="user-content-citation" class="anchor" aria-label="永久链接：引文" href="#citation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您发现该项目对您的研究有用，请考虑引用：</font></font></p>
<div class="highlight highlight-text-bibtex notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">@article</span>{<span class="pl-en">chen2023internvl</span>,
  <span class="pl-s">title</span>=<span class="pl-s"><span class="pl-pds">{</span>InternVL: Scaling up Vision Foundation Models and Aligning for Generic Visual-Linguistic Tasks<span class="pl-pds">}</span></span>,
  <span class="pl-s">author</span>=<span class="pl-s"><span class="pl-pds">{</span>Chen, Zhe and Wu, Jiannan and Wang, Wenhai and Su, Weijie and Chen, Guo and Xing, Sen and Zhong, Muyan and Zhang, Qinglong and Zhu, Xizhou and Lu, Lewei and Li, Bin and Luo, Ping and Lu, Tong and Qiao, Yu and Dai, Jifeng<span class="pl-pds">}</span></span>,
  <span class="pl-s">journal</span>=<span class="pl-s"><span class="pl-pds">{</span>arXiv preprint arXiv:2312.14238<span class="pl-pds">}</span></span>,
  <span class="pl-s">year</span>=<span class="pl-s"><span class="pl-pds">{</span>2023<span class="pl-pds">}</span></span>
}

<span class="pl-k">@article</span>{<span class="pl-en">chen2024far</span>,
  <span class="pl-s">title</span>=<span class="pl-s"><span class="pl-pds">{</span>How Far Are We to GPT-4V? Closing the Gap to Commercial Multimodal Models with Open-Source Suites<span class="pl-pds">}</span></span>,
  <span class="pl-s">author</span>=<span class="pl-s"><span class="pl-pds">{</span>Chen, Zhe and Wang, Weiyun and Tian, Hao and Ye, Shenglong and Gao, Zhangwei and Cui, Erfei and Tong, Wenwen and Hu, Kongzhi and Luo, Jiapeng and Ma, Zheng and others<span class="pl-pds">}</span></span>,
  <span class="pl-s">journal</span>=<span class="pl-s"><span class="pl-pds">{</span>arXiv preprint arXiv:2404.16821<span class="pl-pds">}</span></span>,
  <span class="pl-s">year</span>=<span class="pl-s"><span class="pl-pds">{</span>2024<span class="pl-pds">}</span></span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="@article{chen2023internvl,
  title={InternVL: Scaling up Vision Foundation Models and Aligning for Generic Visual-Linguistic Tasks},
  author={Chen, Zhe and Wu, Jiannan and Wang, Wenhai and Su, Weijie and Chen, Guo and Xing, Sen and Zhong, Muyan and Zhang, Qinglong and Zhu, Xizhou and Lu, Lewei and Li, Bin and Luo, Ping and Lu, Tong and Qiao, Yu and Dai, Jifeng},
  journal={arXiv preprint arXiv:2312.14238},
  year={2023}
}

@article{chen2024far,
  title={How Far Are We to GPT-4V? Closing the Gap to Commercial Multimodal Models with Open-Source Suites},
  author={Chen, Zhe and Wang, Weiyun and Tian, Hao and Ye, Shenglong and Gao, Zhangwei and Cui, Erfei and Tong, Wenwen and Hu, Kongzhi and Luo, Jiapeng and Ma, Zheng and others},
  journal={arXiv preprint arXiv:2404.16821},
  year={2024}
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">致谢</font></font></h2><a id="user-content-acknowledgement" class="anchor" aria-label="永久链接：致谢" href="#acknowledgement"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">InternVL 参考以下项目的代码构建：</font></font><a href="https://github.com/openai/CLIP"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenAI CLIP</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://github.com/mlfoundations/open_clip"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Open CLIP</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://github.com/LAION-AI/CLIP_benchmark"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CLIP Benchmark</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://github.com/baaivision/EVA/tree/master"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">EVA</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://github.com/OpenGVLab/InternImage"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">InternImage</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://github.com/czczup/ViT-Adapter"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ViT-Adapter</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://github.com/open-mmlab/mmsegmentation"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MMSegmentation</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://github.com/huggingface/transformers"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Transformers</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://github.com/facebookresearch/dinov2"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DINOv2</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://github.com/salesforce/LAVIS/tree/main/projects/blip2"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BLIP-2</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://github.com/QwenLM/Qwen-VL/tree/master/eval_mm"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Qwen-VL</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://github.com/haotian-liu/LLaVA"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LLaVA-1.5</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。感谢他们出色的工作！</font></font></p>
<hr>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您想加入我们的微信群，请扫描以下二维码添加我们的助手为微信好友：</font></font></p>
<p align="center" dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://private-user-images.githubusercontent.com/26198430/253845075-e3f0807f-956a-474e-8fd2-1f7c22d73997.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTQ2MzMyNjksIm5iZiI6MTcxNDYzMjk2OSwicGF0aCI6Ii8yNjE5ODQzMC8yNTM4NDUwNzUtZTNmMDgwN2YtOTU2YS00NzRlLThmZDItMWY3YzIyZDczOTk3LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA1MDIlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNTAyVDA2NTYwOVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWZiYzNlNjM5NzYxMDEwZjgxMjljOTFiNGFhNWQ5NWU5YTg3MWM1ZjNjNzNkOWE0MDYxNTAzOWM0ZWZiNmY5YjAmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.aGtTXv1samBjLKY7J4cRQMG7wkH70DmX2csR15HwGZY"><img width="300" alt="图像" src="https://private-user-images.githubusercontent.com/26198430/253845075-e3f0807f-956a-474e-8fd2-1f7c22d73997.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTQ2MzMyNjksIm5iZiI6MTcxNDYzMjk2OSwicGF0aCI6Ii8yNjE5ODQzMC8yNTM4NDUwNzUtZTNmMDgwN2YtOTU2YS00NzRlLThmZDItMWY3YzIyZDczOTk3LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA1MDIlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNTAyVDA2NTYwOVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWZiYzNlNjM5NzYxMDEwZjgxMjljOTFiNGFhNWQ5NWU5YTg3MWM1ZjNjNzNkOWE0MDYxNTAzOWM0ZWZiNmY5YjAmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.aGtTXv1samBjLKY7J4cRQMG7wkH70DmX2csR15HwGZY" style="max-width: 100%;"></a></p>
</article></div>
