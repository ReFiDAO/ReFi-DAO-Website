# ReFi DAO Website

Official website for ReFi DAO - A network society to regenerate the earth.

Built with [Quartz](https://quartz.jzhao.xyz/) static site generator.

## About

ReFi DAO is a network society focused on developing strategic services and public goods for the Regenerative Finance ecosystem. Our services include sense-making, education, opportunity development, fundraising support, onboarding and empowerment.

## Development

### Prerequisites

- Node.js v22+ (see `.node-version` for the specific version)
- npm v10.9.2+

### Setup

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npx quartz build --serve
```

The site will be available at `http://localhost:8080`

### Build for Production

```bash
npx quartz build
```

## Project Structure

```
ReFi-DAO-Website/
├── content/                    # Markdown content files
│   ├── index.md               # Homepage
│   ├── about/                 # About ReFi DAO
│   ├── resources-hub/        # Resources Hub (migrated from regencoordination.xyz/refidao)
│   ├── community/
│   │   ├── local-nodes.md    # Interactive map of local nodes
│   │   ├── guilds/           # Online guilds
│   │   └── working-groups/   # Working groups
│   ├── media/                # Media hub
│   └── nodes/                # Links to federated local node repos
├── assets/                    # Static assets
│   ├── images/               # Images
│   └── media/                # Media files
├── quartz/                    # Quartz framework files
├── quartz.config.ts          # Quartz configuration
└── package.json              # Dependencies
```

## Deployment

The site is automatically deployed via GitHub Actions when changes are pushed to the `main` branch.

- **GitHub Pages:** https://refidao.com
- **Repository:** https://github.com/ReFiDAO/ReFi-DAO-Website

## Migration Status

- ✅ Phase 0: Current Website Documentation
- 🚧 Phase 0.5: Repository Setup & Organization (in progress)
- ⏳ Phase 1: Content Extraction & Organization
- ⏳ Phase 2: Database Migration from Airtable
- ⏳ Phase 3: Feature Implementation
- ⏳ Phase 4: Design & Styling
- ⏳ Phase 5: Deployment
- ⏳ Phase 6: Content Migration
- ⏳ Phase 7: SEO & Performance

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on contributing to this project.

## License

[Add license information]

## Contact

For questions or contributions, contact us at [community@refidao.com](mailto:community@refidao.com)
