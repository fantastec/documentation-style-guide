# Colony Documentation Style Guide

A basic style guide to help ensure Colony documentation is consistent between authors and codebases.

### Back-end

As per convention this is treated as a compound noun and should always be hyphenated.

- Back-end ✅
- back-end ✅
- Back End ❌
- back end ❌

### British English vs American English

- At the author's discretion, but pick a style and be consistent. Also consider that the documentation and code may be absorbed into a non-UK-based team.

### Client side vs client-side

When used as a noun, seperate with a space. When used as a compound adjective, hyphenate.

- "when used on the client side" ✅
- "the client-side view models" ✅
- "depending on the client side architecture" ❌
- "which only applies to the client-side" ❌

### Codebase

When using the term codebase, use as a compound noun with no space or hyphen.
- Codebase ✅
- codebase ✅
- Code base ❌
- code-base ❌

### Colony Terminology

When referring to internal Colony terminology, always suround with quotes on first mention, and make an effort to explain the meaning in as close to layman's terms as possible.

- 'each cortex "module" is essentially a template to be rendered'
- 'internally, a request uses a system of "builders" and "queries"'.

### Front-end

As per convention this is treated as a compound noun and should always be hyphenated.

- Front-end ✅
- front-end ✅
- Front End ❌
- Front end ❌

### Headings

- Use title case for all headings. If the title contains a hypenated term (e.g. Front-end), only capitalize the first word.

- **Getting Started with CortexJS**  ✅
- **Setting up a Front-end Dev Environment**  ✅
- **Connecting API endpoints** ❌
- **Front-End Back-End Workflow ❌

### Inline code

When referring to classes, variables, members, filename, or anything which is actually referring to code, inline with a single backtick on each side.

- "in this case, `ControllerBase` is extended" ✅
- "the `layout` property refers to the name of an associated module" ✅
- "each item in routes.json represents a discrete URL structure" ✅

### Introductions

Aim to introduce top-level documentation (./README.md) with a short summary describing the goal or purpose of the codebase in as close to layman's terms as possible.

### JavaScript

Always use the [official](https://developer.mozilla.org/en-US/docs/Web/JavaScript) spelling with an uppercase "J" and "S".

- JavaScript ✅
- Javascript ❌
- javascript ❌

### .NET

Where possible, use the [official](https://www.microsoft.com/net) spelling in all uppercase, preceeded by a "." character. In situations where non-word characters are illegal or stripped out (e.g. URIs or slugs) use "dotnet" in all lowercase.

- .NET ✅
- /cortex-dotnet/ ✅
- .Net ❌
- .net ❌
- DotNet ❌

# Numbers

Use words for one through nine, and digits for 10 and above.

- "the codebase consists of four projects" ✅
- "all 15 controllers enherit from a single base class" ✅
- "data may be populated in one of 2 ways" ❌

### Server side vs server-side

When used as a stand-alone noun, seperate with a space. When used as a compound adjective, hyphenate.

- "when used on the server side" ✅
- "the server-side view models" ✅
- "depending on the server side architecture" ❌
- "which only applies to the server-side" ❌

### Subjectivity

Avoid unneccessary subjective descriptions of our code/product. Stay objective and technical.

- "providing a slick user experience" ❌
- "an innovative architecture" ❌

### Third-party Software

When referring to third-party software, vendors, or technologies (e.g. Microsoft, Express, AutoMapper, Node.js), always treat as proper nouns and capitalize the first letter. If an acronym, always fully capitalize. Refer to the vendor for the official spelling/casing.

If integrated with Colony, or of any importance to the documentation, **hyperlink on first mention**.

- Microsoft ✅
- Chrome ✅
- GitHub ✅
- node ❌
- Json ❌
- Github ❌
- webpack ❌
