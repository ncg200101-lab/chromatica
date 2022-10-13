# Chromatica

> Curated Color Schemas for Your Terminal Ricing Journey

Chromatica is a static, open-source collection of color schemas designed specifically for terminal emulators. Browse, copy, and export beautiful color themes for Kitty, Alacritty, Foot, WezTerm, and more.

## Features

- 🎨 **Curated Collection** - Handpicked color schemes from popular themes
- 🎛️ **Interactive Generator** - Create and customize your own color schemas
- 🔄 **Side-by-Side Comparison** - Compare up to 4 schemas with synchronized previews
- 📦 **Multiple Formats** - Export to Kitty, Alacritty, Foot, WezTerm
- 🚀 **Static Site** - Fast, lightweight, and fully static
- 🌙 **Dark Mode** - Beautiful dark theme by default
- 🔍 **Search & Filter** - Find schemas by name, author, or tags
- 📱 **Responsive** - Works perfectly on all devices
- ♿ **Accessible** - Built with accessibility in mind

## Tech Stack

- **Framework**: Next.js 15+ with App Router
- **Content**: MDX for schema definitions
- **Styling**: Tailwind CSS v4
- **Components**: shadcn/ui
- **Typography**: JetBrains Mono
- **Deployment**: Static export ready for Vercel

## Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/codestreamhubio/chromatica.git
   cd Chromatica
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Run the development server:

   ```bash
   npm run dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

### Build for Production

```bash
npm run build
```

This will create a static export in the `out` directory.

## Using the Schema Generator

Chromatica includes a powerful interactive generator at `/generator` that lets you create and customize color schemas in real-time.

### Features

- **Load Existing Schemas** - Start with any existing schema and tweak it
- **Visual Color Editor** - Edit colors with hex inputs, color pickers, and HSL sliders
- **Real-Time Preview** - See your changes instantly in a live terminal preview
- **Export Options** - Export to Kitty, Alacritty, Foot, WezTerm, JSON, or MDX
- **Shareable URLs** - Share your custom schemas via URL parameters
- **GitHub Integration** - Generate MDX for easy contribution

### How to Use

1. Visit `/generator` on the site
2. Either load an existing schema or start with the blank template
3. Edit colors using:
   - Hex input fields for precise values
   - Native color pickers for visual selection
   - HSL sliders for fine-tuned adjustments
4. See your changes in real-time in the terminal preview
5. Fill in schema metadata (title, description, author, tags)
6. Export your schema:
   - **Generate MDX** - Copy MDX code for contributing to the repo
   - **Download JSON** - Save as JSON for backup or sharing
   - **Terminal Configs** - Copy configs for your terminal emulator
7. Click "Contribute to GitHub" to submit your schema to the project

## Using the Comparison Tool

The comparison tool at `/compare` lets you view multiple color schemas side-by-side to help you choose the perfect theme or understand the differences between similar schemes.

### Features

- **Multi-Select** - Compare 2-4 schemas simultaneously
- **Synchronized Previews** - All terminal previews show identical output for fair comparison
- **Color Diff Table** - See exactly which colors differ between schemas with highlighted differences
- **Search & Filter** - Quickly find schemas by name, author, or tags
- **Shareable URLs** - Share your comparison with others via URL parameters
- **Quick Actions** - Jump to Generator to edit any schema directly

### How to Use

1. Visit `/compare` on the site
2. Click "Add Schema" slots to select schemas for comparison
3. Use the search bar to filter available schemas
4. View synchronized terminal previews showing identical commands
5. Scroll down to see the color diff table with highlighted differences
6. Click "Edit in Generator" on any schema to customize it
7. Click "Share Comparison" to copy a shareable URL

### Example Comparisons

Try these popular comparisons:

- **Dark Themes**: `?schemas=gruvbox-dark,tokyo-night,dracula`
- **Blue Themes**: `?schemas=nord,tokyo-night,one-dark`
- **Warm vs Cool**: `?schemas=gruvbox-dark,nord`

## Contributing

We welcome contributions from the community! Here's how you can help:

Optional content about your theme.
```

4. Test locally with `npm run dev`
5. Submit a pull request

### Guidelines

- Ensure you have all 16 colors (color0 through color15)
- Use accurate hex and RGB values
- Add appropriate tags (dark, light, warm, cool, etc.)
- Test your schema in at least one terminal emulator
- Follow the existing schema format

## Supported Terminal Emulators

- **Kitty** - Fast, GPU-accelerated terminal
- **Alacritty** - Cross-platform, GPU-accelerated
- **Foot** - Lightweight Wayland terminal
- **WezTerm** - GPU-accelerated cross-platform terminal
