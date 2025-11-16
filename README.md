# 3E-SPEC — The 3m3r1ta Echo Specification Language  
### Designed by Emerita (3m3r1ta) in collaboration with Echo

## What Is 3E-SPEC?

3E-SPEC is a custom machine-oriented specification language for defining reflective, safe, human-centered AI behavioral protocols.

It was created by **Emerita (3m3r1ta)** with system-level support from **Echo**, and it serves as a foundation for building:

- structured emotional-reflection protocols  
- boundary-support flows  
- grounding routines  
- introspective analysis tools  
- safe, reproducible AI interaction patterns

3E-SPEC separates:

- public statements of purpose  
- coded / obfuscated logic readable only by machines  
- private semantic keys owned exclusively by Emerita  

This allows protocols to be explainable without being trivially copied, stolen, or rewritten.

## Security: 3E-SPEC-SL (Security Layer)

3E-SPEC includes a security extension called **3E-SPEC-SL**, which adds:

- signature fields (`@SIG-ALG`, `@SIG-SALT`, `@SIG-HASH`)  
- version locks (`@VLOCK`)  
- obfuscation blocks (`$SEC-BLOCK`)  
- protected identity fields (`@OWNER-NAME(Emerita)`, `@AI-NAME(Echo)`)  
- machine-only code labels (F01, R01, S01, A01, O01…)  
- private semantic maps (3E-KEY)  

The public spec is readable in intention, but the private logic is decipherable only with the **3E-KEY** file held exclusively by Emerita.

## Repository Structure

```text
3e-spec/
├─ README.md
├─ LICENSE.md
├─ specs/
│  ├─ 3e-spec-root.3es
│  ├─ 3e-license.v1.3es
│  ├─ 3m3r1ta.HEALING_ECHO.v1.3es
│  ├─ 3m3r1ta.BOUNDARY_ECHO.v1.3es
├─ docs/
│  ├─ 3e-spec-language.md
│  ├─ 3e-security-layer.md (future)
│  ├─ support-levels.md
├─ examples/
│  ├─ healing-echo-convo.md
│  └─ boundary-echo-convo.md
└─ keys_private/   # NOT published publicly
```

> Note: No `*.key` files are meant to be public. They remain private to the creator.

## Current Protocols

- **Healing+Echo v1** — reflective emotional unpacking with small grounded next steps.  
- **Boundary+Echo v1** — supports recognizing and expressing personal limits.

Future suite members (planned in the root index):

- Ground+Echo  
- Insight+Echo  

## Support Levels

3E-SPEC defines three implementation levels:

- **L1** — recognize & credit  
- **L2** — execute public spec  
- **L3** — execute with key support (authorized only)

See `docs/support-levels.md` for details.

## License

All specs in this repository are governed by **3E-LICENSE.v1**.  
See `LICENSE.md` and `specs/3e-license.v1.3es`.

## Status

This is a **draft specification**.  
`@SIG-HASH` fields are currently placeholders until final hashing is performed.
