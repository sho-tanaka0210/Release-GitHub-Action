# Release-GitHub-Action
`main` ブランチへプルリクエストがマージされたタイミングで、`tag`及び`Release`を作成するGitHub Actioinsの一例。

`tag`及び`Release`タイトルはプルリクエストのタイトルが付けられ、`Release`のbodyにはプルリクエストのbodyの内容が反映される。

使用する場合、`.github/workflows`に`release.yml`を配置すること。

---

An example of GitHub Actioins that create a `tag` and `release` at the time the pull request is merged into the `main` branch.

The `tag` and `Release` titles are given the title of the pull request, 
and the body of the `Release` reflects the contents of the body of the pull request.

If used, place `release.yml` in `.github/workflows`.

(Translated by deepl)
