# Figma-to-Code Portfolio Example

A demonstration project showing how to implement Figma designs in code using [Figma-Context-MCP](https://github.com/GLips/Figma-Context-MCP) with AI-powered coding tools. This project converts Figma design templates into a responsive developer portfolio website built with Next.js and TailwindCSS.

## Demo Figma Designs

This project demonstrates implementation of the following Figma designs:

1. [Minimal Modern Landing Page UI](https://www.figma.com/design/UnpEzljS3aFCzwBgRf4GL1/Minimal-Modern-Landing-Page-UI-%7C-Minimal-Landing-Page-%7C-Modern-UI-(Community)?node-id=0-9&t=A7qtYt7xF4x9LqmL-0)
2. [Portfolio Website Template](https://www.figma.com/design/xGfvztxn4UI5ijZ9NPEdyZ/Portofolio-Website-Template-(Community)?node-id=813-137&t=1FTX52emLN8KMC45-0)

## Tip regarding Figma MCP

- When opening a new tab if you are using Cursor then you need to readd the MCP and remove the old one
- You will probably need few iterations to get as close as possible to figma design result.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine.

### Prerequisites

- Node.js (v18+ recommended)
- npm, yarn, or pnpm
- Figma API key (for accessing Figma designs)
- AI coding tool like Cursor, Windsurf, or Cline

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/figma-to-code-example.git
cd figma-to-code-example
```

2. Install dependencies:
```bash
npm install
# or
yarn install
# or
pnpm install
```

3. Setting up Figma-Context-MCP

Run the server quickly without installing or building the repo:

```bash
npx figma-developer-mcp --figma-api-key=your_figma_api_key_here
```


## Using with AI Coding Tools

### Cursor

1. Start the MCP server
2. In Cursor, go to Settings > MCP and connect to the MCP server (http://localhost:3333/sse using sse option)
3. Open Agent mode in Composer
4. Paste a Figma link (either full file or specific component) and ask Cursor to implement it

## Built With

- [Next.js](https://nextjs.org/) - The React framework for production
- [TailwindCSS](https://tailwindcss.com/) - A utility-first CSS framework
- [Figma-Context-MCP](https://github.com/GLips/Figma-Context-MCP) - MCP server for Figma integration

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

* Original Figma designs from Figma community templates
* [GLips](https://github.com/GLips) for creating the Figma-Context-MCP tool
