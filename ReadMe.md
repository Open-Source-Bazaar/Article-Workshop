# Article Workshop

A template repository for writing or translating articles, which is based on [GitHub][1] infrastructure & [flow][2], and can replace [Crowdin][3]-like SaaS for free.

![GitHub flow](https://cdn.hashnode.com/res/hashnode/image/upload/v1668070000889/rvf5Hx764.png)

[![Fetch Web pages](https://github.com/Open-Source-Bazaar/Article-Workshop/actions/workflows/crawler.yml/badge.svg)][4]
[![Format Markdown files](https://github.com/Open-Source-Bazaar/Article-Workshop/actions/workflows/formatter.yml/badge.svg)][5]

## Usage

### Maintaner

1. Install GitHub apps in your organization or account:

   1. [Probot settings][6]: set up Issue labels & Pull Request rules
   2. [PR badge][7]: set up Online [VS Code][8] editor entries in Pull Request description

2. Click the **[<kbd>Use this template</kbd>][9] button** on the top of this GitHub repository's home page, then create your own repository in the app-installed namespace above

3. Replace all the URLs & Mention tags in the new repository with your own namespace

4. Recommend to add a [Notification step in GitHub actions][10] for your Team IM app

### Translator

1. Add a new article in [Crawler issue form][11], and wait for minutes

2. Crawler bot will comment on the issue with an **editor link** of your original article

3. Translate the article in the editor, and save it with <kbd>Propose changes</kbd> button, then create a Pull Request for your translation

4. If you haven't translate the full article before your first saving, you can click one of the editor buttons in your Pull Request home page to finish your translation

### Reviewer

Follow the [GitHub official guide of Pull Request reviewing][12].

## Inspiration

1. https://github.com/freeCodeCamp/chinese
2. https://github.com/orgs/FreeCodeCamp-Chengdu/projects/4
3. https://github.com/kaiyuanshe/open-source-articles

[1]: https://github.com/
[2]: https://githubflow.github.io/
[3]: https://crowdin.com/
[4]: https://github.com/Open-Source-Bazaar/Article-Workshop/actions/workflows/crawler.yml
[5]: https://github.com/Open-Source-Bazaar/Article-Workshop/actions/workflows/formatter.yml
[6]: https://probot.github.io/apps/settings/
[7]: https://pullrequestbadge.com/
[8]: https://code.visualstudio.com/
[9]: https://github.com/new?template_name=Article-Workshop&template_owner=Open-Source-Bazaar
[10]: https://github.com/Open-Source-Bazaar/Article-Workshop/blob/master/.github/workflows/crawler.yml#L26-L46
[11]: https://github.com/Open-Source-Bazaar/Article-Workshop/issues/new/choose
[12]: https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests
