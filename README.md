# 👋 Hi, I'm Shingo Kawamura (川村慎吾)

Infrastructure engineer, Perl developer, and open-source maintainer based in Tokyo.

I work across **large-scale infrastructure**, **developer tooling**, and **software maintenance**. A recurring theme in my work is keeping useful systems dependable over time: preserving compatibility, reducing operational friction, and maintaining software that other systems quietly depend on.

I also run **[Open Steward](https://kawamurashingo.github.io/open-steward/)** — a public software-stewardship effort to create, rescue, and sustain software worth keeping.

## What I work on

### 🛟 CPAN maintenance and ecosystem stewardship

I run **[CPAN Rescue](https://github.com/kawamurashingo/cpan-rescue)**, an effort to identify important Perl distributions that are abandoned or under-maintained and bring them back into responsible maintenance.

Current work includes:

- **Devel::CallChecker** — adopted and released as 0.010 after downstream compatibility validation
- **Log::Any::Adapter::Screen** — adopted after an upstream regression-test contribution
- **Dist::CheckConflicts** — maintenance contribution awaiting upstream
- **Dist::Zilla::Plugin::MetaProvides family** — confirmed `ADOPTME` rescue target with active downstream users
- **DBD::ODBC** — investigating long-term maintenance status, testability, and rescue scope

The focus is conservative maintenance: tests, compatibility, CI, metadata, small fixes, and careful downstream validation rather than rewrites.

### 🧰 Practical open-source tools

I build small, durable tools for environments where simplicity and deployability matter.

- **[JQ-Lite](https://github.com/kawamurashingo/JQ-Lite)** — jq-compatible JSON processor in pure Perl
- **[HTTP-API-Core](https://github.com/kawamurashingo/HTTP-API-Core)** — reusable Perl foundation for HTTP API clients

### 🖥 Infrastructure engineering

My professional background is in Linux and large-scale infrastructure operations, including:

- Linux system administration and SRE
- datacenter and platform migrations involving **10,000+ systems**
- CDN, SSL, load balancer, storage, and virtualization migrations
- enterprise infrastructure modernization and cloud adoption
- Akamai, VMware ESXi, NetApp, Azure, and GCP environments

I tend to approach software from an operations perspective: predictable behavior, clear failure modes, compatibility, and maintainability matter as much as features.

## Selected projects

| Project | Focus |
| --- | --- |
| **[cpan-rescue](https://github.com/kawamurashingo/cpan-rescue)** | Rescue and long-term maintenance of abandoned or under-maintained CPAN distributions |
| **[Devel-CallChecker](https://github.com/kawamurashingo/Devel-CallChecker)** | Maintenance of a low-level Perl XS compatibility module with broad downstream impact |
| **[HTTP-API-Core](https://github.com/kawamurashingo/HTTP-API-Core)** | Stable reusable core for Perl HTTP API clients |
| **[JQ-Lite](https://github.com/kawamurashingo/JQ-Lite)** | Pure-Perl jq-compatible JSON processor |

## Technical focus

- Perl and shell tooling
- CPAN distribution maintenance
- compatibility and regression testing
- Linux infrastructure and operations
- stable CLI and API design
- CI and release engineering
- automation for restricted, legacy, and long-lived environments

## Background

**Rakuten, Inc. — 2011 to Present**

Worked across system administration, SRE, and technical account management roles, with a focus on large-scale infrastructure reliability and migration work.

Before that, I studied life sciences and bioinformatics at **Meiji University**, working with genomic data analysis and biological databases. That experience shaped how I think about reproducibility, data processing, and software-supported research.

## What I value in software

I like software that is boring in the best possible way:

- well tested
- compatible
- understandable
- easy to operate
- careful about downstream users
- maintained for the long term

A lot of my open-source work is about making existing software more trustworthy rather than making it more complicated.

## Contact

- GitHub: https://github.com/kawamurashingo
- LinkedIn: https://www.linkedin.com/in/shingo-kawamura-20452443
