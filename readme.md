# SCELC Salesforce Conceptual Diagram

[Mermaid](https://mermaid.ai/open-source/intro/) diagram of objects and relationships in SCELC's Salesforce instance. Run `pnpm install` to get the mermaid JS file, then open index.html in a browser.

To create an image from the plain text file:

`pnx @mermaid-js/mermaid-cli --input mermaid.txt --cssFile cli.css -o diagram.png`

Note the cli.css differs from the `<style>` tag in the HTML because it does not have the parent HTML elements like `#diagram` in it. You'd have to include the browser's whole default stylesheet to get the precise same result, I think.
