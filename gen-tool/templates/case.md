<a id="cases-{{{case_no}}}"></a>
### {{{t.case_caption}}} {{{case_no}}}{{{t.colon}}}{{{title}}}

{{#capability_type}}
<p>
{{#capability_type_physics}}<img src="https://img.shields.io/badge/Type-Physics-3b82f6?style=flat-square" alt="Physics">{{/capability_type_physics}}
{{#capability_type_cinematic}}<img src="https://img.shields.io/badge/Type-Cinematic_Photo-8b5cf6?style=flat-square" alt="Cinematic Photo">{{/capability_type_cinematic}}
{{#capability_type_typography}}<img src="https://img.shields.io/badge/Type-Typography-10b981?style=flat-square" alt="Typography">{{/capability_type_typography}}
{{#capability_type_multi_character}}<img src="https://img.shields.io/badge/Type-Multi_Character-f59e0b?style=flat-square" alt="Multi Character">{{/capability_type_multi_character}}
{{#capability_type_stylized}}<img src="https://img.shields.io/badge/Type-Stylized_Characters-ec4899?style=flat-square" alt="Stylized Characters">{{/capability_type_stylized}}
{{#capability_type_surreal}}<img src="https://img.shields.io/badge/Type-Surreal_Concepts-06b6d4?style=flat-square" alt="Surreal Concepts">{{/capability_type_surreal}}
{{#capability_type_maps}}<img src="https://img.shields.io/badge/Type-Maps_Layout-eab308?style=flat-square" alt="Maps Layout">{{/capability_type_maps}}
{{#capability_type_pattern}}<img src="https://img.shields.io/badge/Type-Pattern_Design-ef4444?style=flat-square" alt="Pattern Design">{{/capability_type_pattern}}
{{#capability_type_editing}}<img src="https://img.shields.io/badge/Type-Image_Editing-6366f1?style=flat-square" alt="Image Editing">{{/capability_type_editing}}
</p>

{{/capability_type}}
<img src="cases/{{{case_no}}}/{{{image}}}" width="300" alt="{{{alt_text}}}"><br>
<sub>Image © 2025 <a href="{{{attribution.image_author_link}}}">{{{attribution.image_author}}}</a>, <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a> • Prompt by <a href="{{{attribution.prompt_author_link}}}">{{{attribution.prompt_author}}}</a> • {{{source_links}}}</sub>

{{#has_reference_images}}
**{{{t.reference_images_caption}}}**

{{#reference_images}}
<img src="cases/{{{case_no}}}/{{{.}}}" width="150" alt="Reference image">
{{/reference_images}}

{{/has_reference_images}}

**{{{t.prompt_caption}}}**

```
{{{prompt}}}
```

{{#submitter}}
**{{{t.submitter_caption}}}** [{{{submitter}}}]({{{submitter_link}}})
{{/submitter}}

---

[⬆️ {{{t.return_to_cases_toc_caption}}}](#cases-toc)
