# Project Context

## Business Context

### Purpose
This project solves [specific problem] for [target users]. The main value proposition is [key benefit].

### Key Stakeholders
- **Product Owner**: [Name/Role]
- **Tech Lead**: [Name/Role]
- **Main Users**: [Description of user base]

### Success Metrics
- [Metric 1]: [Target]
- [Metric 2]: [Target]
- [Metric 3]: [Target]

## Technical Context

### Technology Stack
- **Frontend**: React 18, TypeScript, Tailwind CSS
- **Backend**: Node.js, Express, PostgreSQL
- **Infrastructure**: AWS (EC2, S3, RDS), Docker
- **CI/CD**: GitHub Actions
- **Monitoring**: DataDog, Sentry

### Key Dependencies
- `react`: UI framework
- `express`: Web server
- `pg`: PostgreSQL client
- `jest`: Testing framework
- [Add your key dependencies]

### External Services
- **Authentication**: Auth0
- **Payments**: Stripe
- **Email**: SendGrid
- **Storage**: AWS S3

### Database Schema
Key tables:
- `users`: User accounts and profiles
- `projects`: User projects and metadata
- `tasks`: Tasks within projects
- `audit_log`: Activity tracking

## Development Context

### Recent Changes
- [Date]: Migrated from REST to GraphQL for [specific feature]
- [Date]: Upgraded to React 18 for concurrent rendering
- [Date]: Implemented caching layer using Redis

### Known Issues
- [Issue 1]: Performance degradation with >1000 items in list view
- [Issue 2]: Mobile Safari has rendering issues on [specific component]
- [Issue 3]: Rate limiting needs improvement

### Technical Debt
- Need to refactor authentication module (using deprecated library)
- Test coverage is below target in `services/` directory
- Database indexes need optimization for reporting queries

## Domain Knowledge

### Key Concepts
- **[Concept 1]**: [Explanation relevant to your domain]
- **[Concept 2]**: [Explanation]
- **[Concept 3]**: [Explanation]

### Business Rules
1. Users can only access projects they own or are shared with them
2. Free tier is limited to 3 projects and 50 tasks
3. Data retention policy is 90 days for deleted items
4. [Your specific business rules]

### Common Workflows
1. **User Onboarding**: Sign up → Email verification → Profile setup → Welcome tutorial
2. **Project Creation**: Create project → Add team members → Set up tasks → Configure notifications
3. **[Your workflows]**: [Description]

## Environment Setup

### Prerequisites
- Node.js 18+
- PostgreSQL 14+
- Docker (for local development)
- AWS CLI (for deployment)

### Environment Variables
```bash
DATABASE_URL=postgresql://localhost/myproject
API_KEY=your_api_key_here
STRIPE_SECRET_KEY=sk_test_...
AUTH0_DOMAIN=your-domain.auth0.com
```

### First-Time Setup
```bash
# Clone and install
git clone [repo-url]
npm install

# Set up database
createdb myproject
npm run migrate

# Start development server
npm run dev
```

## Deployment

### Environments
- **Development**: Auto-deploys from `develop` branch
- **Staging**: Auto-deploys from `staging` branch  
- **Production**: Manual deployment from `main` branch after approval

### Deployment Checklist
- [ ] All tests passing
- [ ] Code review approved
- [ ] CHANGELOG.md updated
- [ ] Database migrations tested
- [ ] Feature flags configured
- [ ] Monitoring alerts configured

## Resources

### Documentation
- [Internal Wiki]: https://wiki.company.com/project
- [API Docs]: https://api.company.com/docs
- [Design System]: https://design.company.com

### Communication
- **Slack**: #project-team
- **Meetings**: Stand-ups Monday/Wednesday/Friday 10am
- **Code Reviews**: Required for all PRs, 2 approvals needed

### Related Projects
- `company-ui-library`: Shared component library
- `company-api-gateway`: API gateway and authentication
- `company-analytics`: Analytics and reporting service
