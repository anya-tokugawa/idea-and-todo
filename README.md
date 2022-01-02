# idea and todo note.
My Idea and todo notepad.

> This idea is PUBLIC DOMAIN.
> But, I want to know your solution for interesting
> ( I don't claim any right to it, and I don't make any teasers about it. )

## List

- [www.md](www.md) ... About World Wide Web
- [Life.md](Life.md) ... How do improve My Life Quality?


## No Sorted

## Product

- Smart Voice Recorder.
  - First, Recording your voices.
  - Second, Learning Your Voices, and transcription to text-file.
  - Third, Identify voiced and generate a file in the Minutes format!

- Simple WYSIWYG Editor.
  - file: ZIP FILE include PureHTML and Git Version Management.
    - append tag id and class from GUI with Style Sheet.
    - and Include CSS managed with pixel adapted dpi.
  - Size Pixel adapted by dpi.
    - example: Selected A4 Paper, DPI: 300px, Papersize: 3508×2480
  - Printing adapted by dpi(**For official documents in strict format**)
  - Dynamic Component via Javascript.
  - for Document.
    - Goal1: formality Document with any styles!
    - Goal2: Use Non-Enginner, alternative Ms Word Editor, Open Standard Editor

- Wiki Helper API (WHAPI)
  - Pure Wiki Server Side API
  - CRUD+Meta
    - CREATE PAGE ... `PUT /path/to/endpoint`
    - READ PAGE ... `GET /path/to/endpoint`
    - UPDATE ... `PUT /path/to/endpoint`
    - DELETE ... `DELETE /path/to/endpoint`
    - Manage Meta Data ... `POST /request/path/name` with JSON.
  - Managed/Insipred Git(One Server One Repository, repository-name: FQDN?)
    - Req: `PUT X-Update-Type: Draft` --> `checkout -b [username]` ---> Save Draft at `[username]` branch.
    - Req: `PUT X-Update-Type: Commit` ---> Save Docs with Commit Mesg at `[username]` branch.
    - Req: `POST /version-control/merge` ---> merge to another branch(e.g. public, main, community_name)
    - Req: `POST /version-control/clone` ---> clone to my server.
    - Req: `POST /version-control/request-pull` ---> req pull.
    - Req: `POST /version-control/pull` ---> pull to upper stream.
    - Req: `POST /version-control/push` ---> push from down stream.
    - Req: `POST /search` with keyword and page ---> return result JSON.
  - Linking Other WHAPI Server
    - GET Search Index Difference Data `POST /public-data/indexes`
    - GET Another Server Information via DHT?, RoutingTable?:  `POST /public-data/servers`
      - IRC/Matrix Integration: Discussion between servers.
      - 

### SNS

- Arbitration System Using Sentiment Judgment, Argument Judgment, and Gathering of Opinions by Natural Language Analysis, Discussion SNS Platform.
- Automatic Information Source Acquisition System on SNS

### Third-Party Services

- Twitter Client liked Nostalgic PC communication services
  - Simple Text-Only realtime Terminal Viewer via ssh or local
  - vim-binding post editor
  - save tweets and search by regex
  - save tweets cron daemon(for offline viewing)

## Analyze

- 全国紙５社HPをスクレイピングし，Macabによる形態素解析，単語出現頻度を見て傾向を探る．あとPresident Onlineとか，Gigazineとかギズモード，デイリーガジェットなど見たい．

## How-to

- QiitaのタイトルをGithub Profile Pagesに貼り付ける方法

## Work efficiency

- MyPage
  - Two Col, right pain is my memorandum, left pain is today schedule or todo.
  - Simple Autentication(Digest on SSL)
  - edit md, output simple html.
  


## Utility

- `mdrandr` .. markdown rendering tool
  - fast
  - **expandability(mdrandr subpackage manager for third-party tool)**
  - calm down usage(good-old unix command usage)
  - support stdin(via pipe)
  - (limited CSS)
  - todo: fork from [github/cmark-gfm](https://github.com/github/cmark-gfm)

- `ipseq` ... output ip addr like `seq` command from CIDR, NetworkAddress/Mask, File... impl. using GoLang.
  - e.g. `ipseq 172.22.1.0/24 | fping -f -` 

- `termrec` ... alternative `script` command. terminal record to Simple readable unix plain text liked CSV, JSON, and so on.
  - and modern style command
  - result output uuid.stdout and uuid.stderr to file by exec
  - timestamp and command list.
 
 ```
 2021-11-12 13:11:03 ls -l
 2021-11-12 13:11:19 cd hoge/bar
 ```

## Learning/Interesting.

### Language

- English(aimed to TOEIC 800+)
- German(interesting)
- Russian(interesting)

### Prog. Lang.

- Rust
- Perl
- Go
