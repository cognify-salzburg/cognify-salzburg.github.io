To test locally, execute

```shell
bundle exec jekyll serve
```

Troubleshoot:
Da am Production-Server eine alte Jekyll version läuft, ist das lokale Deployment etwas mühsam.

- Anleitung befolgen https://jekyllrb.com/docs/ (Dependencies installieren!)

- Wenn ein Package Probleme macht bei der Installation: `bundle update <package>`
    (z.B. `bundle update nokogiri`)

- Änderungen an der _config.yml:

    1. Lösche `Exclude Block`
    2. Füge `excerpt_separator: ""` zu den Build-Settings hinzu


