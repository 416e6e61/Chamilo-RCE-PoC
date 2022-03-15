# Chamilo LMS Authenticated RCE

Chamilo uses the mPDF/Mpdf library to convert HTML to PDF. This can be abused by people able to edit the HTML (so with edition permissions) to trigger a Remote Code Execution vulnerability.
This affects all 1.11.* versions.

[Reference](https://support.chamilo.org/projects/chamilo-18/wiki/Security_issues#Issue-93-2022-03-01-High-impact-Low-risk-SSRF-and-Phar-Deserialization-vulnerability-that-lead-to-remote-code-execution)

![PoC](DeepinScreenshot_select-area_20220228154101.png?raw=true "Title")
