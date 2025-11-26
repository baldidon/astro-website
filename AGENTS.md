# Agent Guidelines

## Commands
- `pnpm dev` - Start development server
- `pnpm build` - Build for production  
- `pnpm format` - Format code with Prettier
- No test framework configured

## Code Style
- Use TypeScript with strict null checks enabled
- Import aliases: `@components/*`, `@layouts/*`, `@config/*`, `@assets/*`, `@/*`
- Astro components: use PascalCase for files, kebab-case for props
- Prettier config: tabs, 100 char width, trailing commas
- Tailwind CSS for styling with class-based approach
- Component interfaces should extend `Props` with clear type definitions
- Use `class:list` for conditional Tailwind classes
- Client-side scripts in `<script>` tags, server-side in frontmatter
- Image assets in `src/assets/images/` with optimized naming
- Follow existing component patterns for consistency