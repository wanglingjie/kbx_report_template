## PDF 模板

Official template for generating RMarkdown PDF document, based on [memor](https://hebrewseniorlife.github.io/memor/index.html).

Official font: `Noto Sans CJK SC`

`memor` config (located at ~/memor-profile.yaml):

```bash
output: 
  memor::pdf_memo:
    use_profile: true
    logo: "logo.png"
    company: 
      name: Knowbox
      email: ds@knowbox.cn
    watermark: Knowbox
    confidential: true
    libertine: true
    chinese: true
    logo_height: 1.2cm
    watermark_color: gray
    footer_on_first_page: true
    toc: true
    lot: false
    lof: false
    number_sections: true
    latex_engine: xelatex
```

