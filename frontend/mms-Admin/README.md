# Mentor-Management-System

Mentors Management system is a people management app that enables proper
coordination of mentors needed to execute projects, ranging from recruitment to off-boarding. Ensue to go through the contributor's wiki below to read more and follow all the instructions.

[hosted link](https://mentor-management-system-team-7-fj6dqhmgi-codehouze.vercel.app/)

[Contributor's wiki](https://github.com/ALCOpenSource/Mentor-Management-System-Team-7/wiki)

## Getting Started

Install dependencies and run the development server:

```bash
npm install

npm run dev
```

Open with your browser to see the result.

## Daily Development

> Please remember to **always** pull the latest changes.

### _Commiting_

Commits must be formated follows:

```console
eg: git commit -m "feat: add new feature"

# For any feature, use feat
# For any documentation, use docs
# For any fix, use fix
# For any refactoring, use refactor
# Make sure to provide short description
```

## Tech

- [Next.js](https://nextjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [DaisyUI](https://daisyui.com/)
- [SWR](https://swr.vercel.app/)

## Generate OpenAPi Client

Install OpenApiGenerator cli

```
npm install @openapitools/openapi-generator-cli -g

```

To generate openApi library, run the following command

```
openapi-generator-cli generate -g typescript-axios --additional-properties=prependFormOrBodyParameters=true -o lib/httpClient -i swagger.yaml --skip-validate-spec

```
