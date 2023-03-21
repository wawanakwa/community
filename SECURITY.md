# `wawanakwa — Security Notice`[^1]

This security notice applies to all [wawanakwa repositories][org-wawanakwa-repos] by default. Its
purpose is to explain the process for reporting security vulnerabilities in our software.

> **Note**
> To see if a repository employs its own security notice, you can look for a `SECURITY.md` file in
> the root of the default branch.

---

## Reporting a Vulnerability

> **Warning**
> It's **IMPERATIVE** that security vulnerabilities are submitted in a confidential manner, using a
> private and secure communication medium. Do **NOT** use a tool like GitHub issues.

When (preferably *if*) you find a vulnerability, we need a list of details to help us identify and
decide on how to solve the problem, as well as deliver security advisories to the community at
large.

1. The website (and page if applicable), repository or otherwise software-related entity where the
   vulnerability is observed,
2. a brief description of the vulnerability,
3. *(optional)* the type of vulnerability (an applicable [OWASP category][owasp-top-10] would be
   nice, too) and
4. a non-destructive example and implementation example of the vulnerability

You must send this information to `<PENDING>`.

## Scope

Some vulnerabilities are not considered to be 'in the scope' of this security notice.

1. 'Volumetric' vulnerabilities, an example of which is overwhelming a service with a high volume of
   requests.
2. Failure to meet standards that are considered 'best practice', an example of which is missing
   security headers.

---

🔐 Thanks for taking the time to read up on our security notice—we really appreciate it!

---

[^1]: This security notice is heavily inspired by [QuiltMC's own][quiltmc-sec-notice].

[org-wawanakwa-repos]: https://github.com/orgs/wawanakwa/repositories
[owasp-top-10]: https://owasp.org/www-project-top-ten/
[quiltmc-sec-notice]: https://quiltmc.org/en/about/security-notice/
