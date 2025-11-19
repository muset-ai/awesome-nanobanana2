# 如何贡献

您可以通过以下两种主要方式来贡献.

There are two main ways you can contribute.

## 方式一：通过 GitHub Issue 快速提交

如果您想快速分享一个案例，或者不太熟悉 Pull Request 流程，可以通过 Issue 提交。

➡️ 点击这里使用模板提交新案例：[提交新案例](https://github.com/company/awesome-nanobanana2/issues/new?template=add_new_example.yml)


## Option 1: Quick Submit via GitHub Issue

If you want to quickly share an example, or if you're less familiar with the Pull Request process, submitting via an Issue is a great option.

➡️ Click here to submit a new example using the template: [Submit New Example](https://github.com/company/awesome-nanobanana2/issues/new?template=add_new_example.yml)

---


## 方式二：通过 Pull Request (PR) 贡献

1. **Clone 仓库并创建本地分支。**

2. **添加新案例：**
* 请参考我们的 [**案例模板目录(./case-template/)**](case-template/) 来准备内容。每个案例应包含两个文件：一个 YAML 文件和一张图片。
* 在 `cases` 目录下创建一个使用下一个可用数字命名的新文件夹（例如命名为 `83`）。  
  **注：** 只需依当前最新编号递增创建，最终编号及排序将在合并时由维护者统一处理。
* **准备图片文件：**
    * 图片尺寸建议宽度为 300px 到 2000px 之间；推荐格式为 JPEG、WebP 或 PNG；文件大小尽量控制在 1MB 以内（如有需要请压缩）。
    * *(可选)* 文件名建议：为图片起一个描述性强且不易重复的文件名（例如：`gold_pendant_necklace.png`）。默认文件名 `case.png`。
* **准备参考图片（可选）：**
    * 如果生成图像时使用了参考图片，请将它们放在同一案例目录中。
    * 参考图片建议命名为 `ref_<description>.png`，例如：`ref_emoji.png`, `ref_style.jpg`。
    * 在 YAML 文件中的 `reference_images` 字段列出所有参考图片文件名。
* **撰写案例 YAML 文件：**
    * 按模板要求填写案例详细信息。
    * 确保在 YAML 文件中正确引用图片文件名和参考图片文件名（如有）。
    * 请务必正确填写以下字段：
        * **原作者名称**（Author）
        * **原作者链接**（Author Link）
        * **原文链接**（Source URL）
    * **语言：** 可以使用任何语言（英语、中文等）提供信息。Prompt 应使用生成时所用的原始语言。

3. 提交更改并在 GitHub 发起 Pull Request。

4. 等待维护者审核并合并 PR。


## Method 2: Contribute via Pull Request (PR)

1. **Clone the repository and create a local branch.**

2. **Add a New Case:**
* Please refer to our [**case template directory (./case-template/)**](case-template/) to prepare your content. Each case should include two files: a YAML file and an image file.
* Create a new folder under the `cases` directory using the next available numeric ID (e.g., a folder named `83`).  
  **Note:** Just follow the latest number available; the final numbering and ordering will be handled by the maintainer during merging.
* **Prepare the image file:**
    * Image size requirements: recommended width between 300px and 2000px; preferred formats are JPEG, WebP, or PNG; please try to keep the file size under 1MB (compress if necessary).
    * *(Optional)* Filename suggestion: choose a descriptive and unique name for the image (e.g., `gold_pendant_necklace.png`). Deafault name is `case.png`.
* **Prepare reference images (Optional):**
    * If you used reference images during generation, place them in the same case directory.
    * Suggested naming: `ref_<description>.png`, e.g., `ref_emoji.png`, `ref_style.jpg`.
    * List all reference image filenames in the `reference_images` field in the YAML file.
* **Write the YAML case file:**
    * Fill in or modify the case details according to the template requirements.
    * Make sure to correctly reference your image filename and reference image filenames (if any) in the YAML.
    * Be sure to correctly fill in the following fields:
        * **Author name**
        * **Author link**
        * **Source URL**
    * **Language:** You can provide the information in any language (English, Chinese, etc.). The prompt should be provided in its original language as used for generation.

3. Commit your changes and open a Pull Request on GitHub.

4. Wait for the maintainer to review and merge your PR.


## 许可协议

通过提交 Pull Request 或 Issue，**您即确认您对所上传的每一个文件拥有版权，或已获得明确授权，并且不可撤销地同意将您的贡献按 CC BY 4.0 许可证发布。**
您上传的图像必须符合以下任一条件：
2. 或您已获得第三方作品的书面使用许可。

严禁上传未经授权的第三方图像。


## License Agreement

By opening a Pull Request or Issue, you **confirm that you own the
copyright or have explicit permission for every file you upload** and
**irrevocably license your contribution under CC BY 4.0**.  
Images must be either:

2. Third-party works for which you hold written permission.

Uploading unlicensed third-party images is prohibited.

---

感谢您的贡献！

Thank you for your contribution!