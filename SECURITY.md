# Security policy

## Reporting a vulnerability

Report it privately through GitHub, not in a public issue.

Go to the Security tab of the repository concerned and choose "Report a vulnerability".
Private vulnerability reporting is enabled on our repositories, so this opens a private
thread with the maintainers. If you cannot reach that form, mail security@zostera.nl and
say which repository it concerns.

Please include the version you tested, what an attacker can do, and the smallest
reproduction you have. A report we cannot reproduce is hard to act on, so a failing test
or a short script is worth more than a description.

## What happens next

We aim to acknowledge a report within a week. These are small open source projects
maintained by a few people, so we would rather give you an honest timescale than a service
level we cannot keep.

If we agree it is a vulnerability, we will tell you what we plan to do and roughly when,
fix it, publish a GitHub Security Advisory, and credit you unless you prefer otherwise.
If we disagree that it is a vulnerability, we will say so and explain why.

## Scope

In scope: anything in the code we publish, including a package rendering attacker
controlled input unsafely, a dependency we pin that is known vulnerable, and our release
and CI workflows.

Out of scope: vulnerabilities in Django, Bootstrap or another upstream project, which
belong with that project; findings from an automated scanner with no demonstrated impact
in our code; and anything requiring an attacker to already control the server the code
runs on.

## AI generated reports

You may use an AI assistant to find or write up a report, the same as for any other
contribution. Say so when you do. A report still has to be reproducible, and one that
cannot be reproduced will be closed without analysis, however it was produced.
