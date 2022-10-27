# TODO

## 参考

🗄
* `education.md` core
* `econ.md` firms
* `sociology.md` print culture
📚
* ✅ Gawande checklist manifesto
* ✅ Hansson getting real/rework
* ✅ Ries lean startup
* ✅ Taylor scientific mgmt
* Toyota production system https://www.youtube.com/watch?v=4E793WS72aU

## current

## queue

SoW
* materials: port sw to stem/dev (symlinks, bash profile, fonts, bin)
* backup
* notes: now/next/done
* bookcase: align fs to notes
* calendar

za
* blog post on how companies should have KM (alongside PM)

## done

* _22_: formalize system of work, separate repos for calendar/contacts, align fs across notes/materials/bookcase, workflow from bash profile
* _20_: termgraph
* _19_: start Vim, switch to VS Code, uninstall Sublime
* _18_: 📙 Hansson crazy Hansson getting real Hansson remote
* _17_: 📙 Hansson rework
* _16_: 📙 Gawade checklist manifesto
* _15_: 📙 Ries lean startup Taylor scientific management

# SoW

📝 Dixit my system of work https://www.princeton.edu/~dixitak/home/dixitwrk.pdf

## calendar

* types: tracking, description
* _logs_: tracking + summarized description on monthly basis
* _calendar_: description for events on daily basis

todo
* logs: port weeks to months + incorporate commit msgs from notes repo
* calendar: figure out impl
* calendar: port in from lianjie/qin

---

* https://news.ycombinator.com/item?id=31574125
* https://github.com/anufrievroman/calcure
* cal/ncal vs. calendar
* calcurse https://www.youtube.com/watch?v=I_-MqgpEWFA
* https://github.com/pimutils/khal
* _CalDAV_: protocol for calendar software https://github.com/pimutils/khal
* not much support https://stevenvanbael.com/open-calendar-task-space-is-a-mess
* iCalendar as alternative https://stevenvanbael.com/open-calendar-task-space-is-a-mess

tracking
* https://github.com/pimutils/todoman
* task warrior https://www.reddit.com/r/commandline/comments/3j5kmg/best_cli_calendars_available_besides_cal/

* NextCloud as option if you want sync https://news.ycombinator.com/item?id=28358463
* vimwiki just for the calendar GUI? hopefully not, file fmt and diruconstraints https://www.youtube.com/watch?v=FsX3SpHiuYw

## contacts

* http://johnkerl.org/misc/jks.html
* port from `photos/correspondence`
* vCard: file fmt for contacts https://github.com/pimutils/mates.rs https://danielmiessler.com/blog/my-custom-contact-sharing-solution
* features: contact info, addresses, calls/msgs, todo, gifts https://www.monicahq.com/features
* https://retool.com/blog/salesforce-for-engineers/
* https://jakobgreenfeld.com/stay-in-touch
* https://www.monicahq.com/features
* https://github.com/pimutils/vdirsyncer

## file system

🗄 `linux.md` denv

```sh
├── /Users/zach/Documents/zvroot
│   └── 📚 BOOKCASE
│   └──── art
│   └──── humanities
│   └──── stem
│   └── 🔍 MATERIALS
│   └──── art
│   └──── humanities
│   └──── stem
│   └── 📝 NOTES
│   └──── art
│   └──── humanties
│   └──── stem
│   └──────────── `dev`  # 📦 submodule
│   └── 🏡 PERSONAL
│   └────── calendar   # 📦🔗 contacts
│   └────── contacts   # 📦
│   └────── photos     # 🔗 calendar/contacts
```

## photos

* need mgmt for tagging
* checkout macOS storage mgmt, archived versions of iPhotos library: `Library.migratedphotolibrary/` `Library.photoslibrary/`
* pillow https://realpython.com/image-processing-with-the-python-pillow-library/
* photos: personal, site design
* https://news.ycombinator.com/item?id=26000113
* site: https://github.com/maxvoltar/photo-stream https://github.com/saimn/sigal
* mgmt: https://github.com/electerious/Lychee https://github.com/hooram/ownphotos https://github.com/photoprism/photoprism

## notes

🗄
* documentation
* `education.md` notes
* `sociology.md` print culture

mine
* BYO fmt https://news.ycombinator.com/item?id=32552782
* CSV + miller + Tabular for Markdown tables? https://miller.readthedocs.io/en/latest/file-formats/#markdown-tabular
* candidates: skating, chords, cooking
* Markdown bad for editing
* Markdown good for flexibility, locality (wouldn't need separate CSV files)
* CSV good for group by, tracking progress
* files to consider: skating, cooking, chords (theory, guitar, instruments/piano)
* ❓ org mode as way to split the difference btw Markdown tables and CSV? https://news.ycombinator.com/item?id=30868696 https://www.youtube.com/watch?v=hnMntOQjs7Q 2:15
> scoping in org modes, current system has enough levels https://www.youtube.com/watch?v=hnMntOQjs7Q 3:15
* evergreen (keep improving) vs. transient (grocery list) https://notes.andymatuschak.org/Evergreen_notes https://www.micahlerner.com/2021/05/23/reflecting-on-2020.html

alternatives
* _Bookstack_: OSS Confluence https://news.ycombinator.com/item?id=29851834
* _Guru_: https://www.getguru.com/
* _Notion_: bad search https://news.ycombinator.com/item?id=30393636
* _Obsidian_: links aka concept map https://www.youtube.com/watch?v=QgbLb6QCK88 https://cmap.ihmc.us/ calendar https://github.com/liamcain/obsidian-calendar-plugin kanban https://github.com/mgmeyers/obsidian-kanban
* _wiki.js_: https://news.ycombinator.com/item?id=23904193
* _Feather Wiki_: https://feather.wiki/

---

apps
* https://github.com/araekiel/jot
* there are many https://news.ycombinator.com/item?id=24898966
* DIY https://news.ycombinator.com/item?id=25299442 https://news.ycombinator.com/item?id=25300547 https://news.ycombinator.com/item?id=25297268
* bi-directional links https://news.ycombinator.com/item?id=26316793
* _GUI_: Muse https://news.ycombinator.com/item?id=24294397 https://museapp.com/ https://news.ycombinator.com/item?id=24572449 Polar https://getpolarized.io/ https://news.ycombinator.com/item?id=24908227 Scrivener https://news.ycombinator.com/item?id=2743202 https://www.blakeboles.com/2020/07/book-story/ SuperNotes https://news.ycombinator.com/item?id=30440275
* _text_: my approach, org mode, mobile client https://gitjournal.io/ https://news.ycombinator.com/item?id=24709393 https://github.com/gnebbia/kb https://xwmx.github.io/nb/ https://news.ycombinator.com/item?id=24810312 https://unixsheikh.com/articles/my-favorite-note-taking-method.html 🗄 `note-structure.png` VimWiki https://www.youtube.com/watch?v=vBJj7YMVn6I https://sive.rs/plaintext https://www.youtube.com/watch?v=NasPBjSev88
* _sink_: http://jrnl.sh/ https://inkdrop.app/ https://github.com/laurent22/joplin https://news.ycombinator.com/item?id=20007108 https://vimwiki.github.io/ https://github.com/notable/notable https://news.ycombinator.com/item?id=21310030 https://github.com/dnote/dnote https://boardist.io/ https://github.com/void-rs/void https://news.ycombinator.com/item?id=23666950 https://news.ycombinator.com/item?id=22694891 https://tkainrad.dev/posts/managing-my-personal-knowledge-base/ https://github.com/polm/deltos https://github.com/karlicoss/HPI links between notes https://obsidian.md/features https://news.ycombinator.com/item?id=23386630 https://github.com/zadam/trilium https://www.pythonpodcast.com/contextualize-topic-modeling-episode-267/ vimwiki https://twitter.com/b0rk/status/1280184085890154497 https://news.ycombinator.com/item?id=23723775 things I've learned (TIL) https://simonwillison.net/2020/Jul/10/self-updating-profile-readme/ https://news.ycombinator.com/item?id=23888799 https://news.ycombinator.com/item?id=23890035 bookmarking apps as an alternative https://klobie.com/v/vzqxyvg/covid-19_prizes https://news.ycombinator.com/item?id=24898373 https://news.ycombinator.com/item?id=25769849 https://news.ycombinator.com/item?id=27513008&utm_term=comment https://blog.nntn.nl/architecture-of-my-life
* evergreen vs. transient https://brainbaking.com/post/2022/04/cool-things-people-do-with-their-blogs/

typing https://www.typelit.io/ https://www.typingclub.com/sportal/ https://news.ycombinator.com/item?id=24696658 https://github.com/lemnos/tt
* most of software is things that are not writing code (thinking, reading) https://news.ycombinator.com/item?id=24851861
* learn to fuckin type http://steve-yegge.blogspot.com/2008/09/programmings-dirtiest-little-secret.html https://drewdevault.com/editing
> Vim traces its ancestry back to the classic Unix editors, vi and ed. These predate the mouse and all of the point-and-click interfaces that came with it. In Vim, everything can be done with the keyboard. For the touch typist, that means Vim does everything faster. - Neil pv xviii

as tool for thought
> Writing is a concentrated form of thinking. I don’t know what I think about certain subjects, even today, until I sit down and try to write about them. - https://www.theparisreview.org/interviews/1887/don-delillo-the-art-of-fiction-no-135-don-delillo
> As Drucker said..."I’m not writing it down to remember it later, I’m writing it down to remember it now." https://macwright.com/2021/03/16/return-of-fancy-tools.html

framing
> This process, far more than any explicit ideological agenda, is the source of most bias in journalism. This source of bias cannot be escaped. Stories without a frame are just an incoherent collection of facts too long and too varied to fit on a page. https://scholars-stage.blogspot.com/2021/02/the-framers-and-framed-notes-on-slate.html
> There was no denying, however, that Diamond’s simple quasi-Darwinian view of human selection was ‘good to think with’. https://www.lrb.co.uk/the-paper/v35/n22/james-c.-scott/crops-towns-government
> There’s some papers, for instance, showing that autistics — they have weaker framing effects, smaller endowment effects, maybe because top-down processing works in a different way. https://conversationswithtyler.com/episodes/daniel-kahneman/

* graphs https://www.dendron.so/
> how could I do this w/ my notes?
* time tracking https://www.youtube.com/watch?v=hFLncuTFo64
* my notetaking on the year as its gone https://jvns.ca/blog/2018/12/23/2018--year-in-review/
* https://gumroad.com/vimtricks
* _metacognition_: note taking w/ comments https://news.ycombinator.com/item?id=24700647
* everything I know https://wiki.nikitavoloboev.xyz/
* alternatives to Wikipedia https://marginalrevolution.com/marginalrevolution/2020/11/saturday-assorted-links-285.html
* information mgmt https://yalebooks.yale.edu/book/9780300165395/too-much-know https://justinehsmith.substack.com/p/what-are-the-humanities
* time tracking https://news.ycombinator.com/item?id=25762715 https://news.ycombinator.com/item?id=25995838
* modeling https://www.kaseyklimes.com/notes/2019/10/16/an-augmented-mind-designing-a-personal-knowledge-base-with-notion

* personal analytics https://simonwillison.net/2020/Nov/14/personal-data-warehouses/ 23:15 https://writings.stephenwolfram.com/2012/03/the-personal-analytics-of-my-life/ https://news.ycombinator.com/item?id=25090218
* works a lot better if you use precise, grep-able language
* note-taking as a form of memory formation http://schuessler.org/i-memorize-things https://news.ycombinator.com/item?id=24710211
* review https://www.benkuhn.net/weekly/

for personal notes, no SSoT; tracking? sjk? individual docs e.g. `lianjie.md`? be nice to have somewhere to capture the tenor; for now that seems to be tracking and the bigger trends to the yearly note 🗄 `sjk/tracking`

Written evidence as ballast against days merging together, the question "what has happened? anything?" And then you look and see, yes, something has happened.

> One thing to note here is that it's important to actually track what you're doing and not just guess at what you're doing. When I've recorded what people do and compare it to what they think they're doing, these are often quite different. It would generally be considered absurd to operate a complex software system without metrics or tracing, but it's normal to operate yourself without metrics or tracing, even though you're much more complex and harder to understand than the software you work on. - https://danluu.com/p95-skill

> So the main value of notebooks may be what writing things down leaves in your head. -  http://paulgraham.com/essay.html

> Rewriting a program often yields a cleaner design. But it would have advantages even if it didn't: you have to understand a program completely to rewrite it, so there is no better way to get one loaded into your head. - http://paulgraham.com/head.html

https://news.ycombinator.com/item?id=22341518

* _process_: https://blog.viktomas.com/posts/my-workflow/
* _notes_: I use outliners https://en.wikipedia.org/wiki/Outliner https://plaintext-productivity.net/ my notes seem to be much improved since the Evernote days, hypothesize that constant summarization improved my cognitive ability (e.g. Kahneman notes were terrible) https://news.ycombinator.com/item?id=31409077 https://news.ycombinator.com/item?id=31407781
* _impl_: Markdown, Git, Vim, typing https://steve-yegge.blogspot.com/2008/09/programmings-dirtiest-little-secret.html 

mental technology / mental bicycles
* note taking
* input: typing ability (Yegge), Vim
* mise en place: books in the room you're working, plain text and tools to search it with
* do-not-disturb

* _content_: kanban board https://wekan.github.io/ + outliner https://www.reddit.com/r/vim/comments/2twafk/what_is_your_favourite_vim_outliner/ don't separate these two https://github.com/klaussinani/taskbook
* _n.b_: not a productivty system (which are bullshit/insane https://guzey.com/productivity) but as dumb as putting like w/ like e.g. "this is about Java, put into `java.md`, this is about Python, put into `python.md`"
* _why?_: I learn faster and more comprehensively than other people
* _personal history_: Word (2006-2012) Evernote (2015.09) deeper into Evernote (2016.09) Markdown (2018.03) Sublime to VS Code, start w/ Vim, start using right hand for command keys (2019.01)
* _marketplaces_: https://www.oxbridgenotes.co.uk/
* _Today I Learned (TIL)_: mini blog; came from Thoughtbot; check out what Williamson using db for https://simonwillison.net/2020/Apr/20/self-rewriting-readme/ https://til.simonwillison.net/ https://questions.wizardzines.com/
* _mind map_: https://markmap.js.org/ https://news.ycombinator.com/item?id=24132631 https://news.ycombinator.com/item?id=27614912

# ZA

README
* good examples https://github.com/pemistahl/grex https://readme.so/
* each little step https://stackoverflow.blog/2020/07/13/tales-from-documentation-write-for-your-dumbest-user
* https://monokh.com/posts/bitcoin-from-scratch-part-1
* README https://healeycodes.com/github/beginners/tutorial/productivity/2019/04/14/writing-an-awesome-github-readme.html
* README-driven devlopment http://tom.preston-werner.com/2010/08/23/readme-driven-development.html http://esr.ibiblio.org/?p=8741
* great READMEs: https://github.com/codenotary/immudb https://github.com/jesseduffield/horcrux https://github.com/pypyr/pypyr/ https://pypyr.io/

encyclopedia
* _Suda_: information on Greek theatre comes https://en.wikipedia.org/wiki/Suda
* 📙 Paris Review chapbook qt. Borges [5]
* wikipedia https://news.ycombinator.com/item?id=31524943

za
* Peter Drucker: coined term 'knowledge worker'
* Slack vs. Zulip, streams vs. topics https://zulip.com/why-zulip/

---

* https://blog.codepen.io/2016/05/10/089-knowledge-management/

1875-present
* military: aristrocratic generals to officer class https://en.wikipedia.org/wiki/The_Soldier_and_the_State
* business: laborers to foreman [Taylor]
* busines: Stripe as paean to written word incorporated in Delaware
* overflowing the firm, trickledown: Bell Labs, Xerox Parc, OSS
* method: Rauch, scientific method
* tired of note taking apps https://news.ycombinator.com/item?id=23888799
* 2022: Notion, Coda, MS Loop https://news.ycombinator.com/item?id=30552142

meetings
* _6-pager_: paragraphs force greater clarity than bullet points https://conorneill.com/2012/11/30/amazon-staff-meetings-no-powerpoint/
* _prove-it_: https://www.fullstory.com/blog/prove-its https://increment.com/frontend/frontend-at-scale/
* https://marginalrevolution.com/marginalrevolution/2022/01/why-are-meetings-so-bad.html

misc
* _make-work_: job that costs more than the value it creates https://news.ycombinator.com/item?id=27300365
* _toil_: work that scales linearly (manual, repetitive, maintains status quo vs. improvement)
* _shift left_: testing and operational readiness from the start https://github.com/returntocorp/semgrep

normalization of deviance https://danluu.com/wat/
> The data are clear that humans are really bad at taking the time to do things that are well understood to incontrovertibly reduce the risk of rare but catastrophic events.
> I've spent a lot of time asking about why things are the way they are, both in areas where things are working well, and in areas where things are going badly. Where things are going badly, everyone has ideas. But where things are going well, as in the small company with the light-touch CEO mentioned above, almost no one has any idea why things work. It's magic. If you ask, people will literally tell you that it seems really similar to some other place they've worked, except that things are magically good instead of being terrible for reasons they don't understand.

* licensing https://www.matthewball.vc/all/what-is-an-entertainment-company-and-why-does-the-answer-matter
* cash flow https://news.ycombinator.com/item?id=25357669
* business is a series of schleps http://www.paulgraham.com/schlep.html https://marginalrevolution.com/marginalrevolution/2020/12/american-ph-ds-are-failing-at-start-ups.html https://www.econlib.org/businesspeople-earn-every-penny/
* bundling and unbundling https://hbr.org/2014/06/how-to-succeed-in-business-by-bundling-and-unbundling
* what people do at work https://waitbutwhy.com/wait-but-who 
* buy vs. rent https://news.ycombinator.com/item?id=24244329
* _consumer research_: entertain industry used to use focus groups but now uses Pilotly https://www.wsj.com/articles/the-data-driven-tech-engine-at-the-heart-of-hollywoods-content-factories-11594440059
* _demand experiment_: explain concept, ask for signup, promise free product if signee shares with friends
* _ERP_: way to share info among LOBs https://retool.com/blog/erp-for-engineers/ https://github.com/frappe/erpnext
* _estimates_: https://news.ycombinator.com/item?id=21067487 
* employee monitoring software https://news.ycombinator.com/item?id=23165579
* _The Goal_: make money; inventory (materials) operational expenses (labor) throughput (sales)
* _management_: be able to talk http://www.paulgraham.com/speak.html esp. w/ confidence about things you don't understand http://paulgraham.com/cred.html no one fired for buying IBM (or hiring HP) https://news.ycombinator.com/item?id=22782097 some interesting practices https://deniseyu.io/2020/05/23/habits-of-high-performing-teams.html non-goals https://github.com/Wilfred/difftastic#non-goals
* _documentation_: needs to be plain text (SSoT) and handbook/readme-first https://about.gitlab.com/company/culture/all-remote/handbook-first-documentation/ sections https://mattsegal.dev/how-to-read-django-docs.html matters more w/ remote https://increment.com/remote/future-of-work-is-written/
* _performance review_: https://news.ycombinator.com/item?id=24374347
* _remote work_ https://basecamp.com/books/remote https://about.gitlab.com/company/culture/all-remote/ https://thorstenball.com/blog/2020/05/22/what-you-think-is-bad-about-remote-work-can-actually-be-good/ 

startup
* ARPU
* cohorts: still worthwhile for non-subscription

cannot tell truth at large companies https://news.ycombinator.com/item?id=22341138

> For individuals the upshot is the same: aim small. It will always suck to work for large organizations, and the larger the organization, the more it will suck. http://www.paulgraham.com/boss.html

* _phases of product_: exploration, growth, exploitation https://softwareengineeringdaily.com/2019/08/28/facebook-engineering-process-with-kent-beck/
* _fitness function_: KPI the team lead agrees on w/ mgmt https://jasoncrawford.org/two-pizza-teams
* closing a business https://www.theguardian.com/technology/2018/aug/21/the-undertakers-of-silicon-valley-how-failure-became-big-business
* _project management_: everything should be version controlled, which means plain text, which means might as well make it part of the repo (why and how in `README.md` and actual PM in `CHANGELOG`) https://www.notion.so/ Trello bear.app
* _Checklist Manifesto_: modern life is very complex (13000 disease per WHO, how many professions does it take to build a skyscraper) current solution is specialization, better solution is the checklist, checklist suited to the complicated (build rocket) vs. complex (raise child)
* _Rework_: decisions are progress, decisions are temporary https://blog.codinghorror.com/go-that-way-really-fast/, ignore details early, planning is guessing, long lists don’t get done, meetings (invite as few people as possible, meet at the site of the problem, end with a solution, make someone responsible for implementation)
* _video conferencing_: https://meet.jit.si/
* find out what people like and they’ll work hard for you https://hbr.org/2018/01/why-people-really-quit-their-jobs
* management is always the problem http://worrydream.com/2017-12-30-alan/ https://www.reddit.com/r/ProgrammerHumor/comments/7jq78i/programmers_always_come_out_on_top/

> I saw management attempt a number of cultural and process changes at LCB. Mostly, those took the form of pronouncements from people with fancy titles. For really important things, they might produce a video, and enforce compliance by making people take a multiple choice quiz after watching the video. - https://danluu.com/wat/

post-mortems at a project level

> We'll do postmortems for "the site was down for 30 seconds", we rarely do postmortems for "this takes 10x as much ops effort as the alternative and it's a death by a thousand papercuts"... I'll sometimes do informal postmortems by asking everyone involved oblique questions about what happened, but more for my own benefit than anything else, because I'm not sure people really want to hear the whole truth. This is especially sensitive if the effort has generated a round of promotions, which seems to be more common the more screwed up the project. The larger the project, the more visibility and promotions, even if the project could have been done with much less effort. - https://danluu.com/wat/

no one tells their manager shit

> Finally, don't expect people to enlighten you and tell you what your blind spots are. Becoming a manager means losing the privilege of being told what's what. It's a trap to think of oneself as just the same reasonable guy and why wouldn't they want to talk to me. The right question is, why would they? Is the risk worth it for them? _Only if they take your org's problem very personally, which most people quite sensibly don't._ Someone telling me what's what is a thing to thank for, but not to count on. - https://yosefk.com/blog/people-can-read-their-managers-mind.html

process is everything

> Everything we’ve looked at so far is a technical problem. Compared to organizational problems, technical problems are straightforward. Distributed systems are considered hard because real systems might drop something like 0.1% of messages, corrupt an even smaller percentage of messages, and see latencies in the microsecond to millisecond range. When I talk to higher-ups and compare what they think they’re saying to what my coworkers think they’re saying, I find that the rate of lost messages is well over 50%, every message gets corrupted, and latency can be months or years. When people imagine how long it should take to build something, they’re often imagining a team that works perfectly and spends 100% of its time coding. But that’s impossible to scale up. The question isn’t whether or not there will inefficiencies, but how much inefficiency. A company that could eliminate organizational inefficiency would be a larger innovation than any tech startup, ever. https://danluu.com/sounds-easy/

management consulting
* Accenture https://news.ycombinator.com/item?id=26969364
> Most top tier management consulting is useless. It boils down to telling executives they should raise prices or avoid taxes in a fancy way, helping one faction in a corporation win an internal battle against another, or aiding a cowardly leader do something he or she knows she should do but is afraid of doing without outside validation. It’s highly overpaid make-work, which is why the movie Office Space resonated. - https://mattstoller.substack.com/p/why-new-york-city-is-on-the-verge

laws https://www.timsommer.be/famous-laws-of-software-development/
* _Brooks Law_: adding more people slows things down [Mythical Man Month, Graham 'The Other Road Ahead' page 70] and you don't write that many lines of code https://varnish-cache.org/docs/6.2/phk/thatslow.html in healthcare industry https://www.newyorker.com/magazine/2018/11/12/why-doctors-hate-their-computers https://www.hillelwayne.com/post/learning-a-language/ https://news.ycombinator.com/item?id=24123372 very wrong about dev tooling https://twitter.com/danluu/status/1343898148863762435
* _Cathedral and the Bazaar_: cathedral (development in private; GCC) vs bazaar (development in public; Linux)
* _Conway's Law_: you ship your org chart
* _Hofstadter's Law_: it always takes longer than you expect, even when you take into account Hofstadter's Law
* _Metcalfe's Law_: value of communication system grows at square of number of users; more about either number of people you know or number of peopple creating stuff (youtube, Tik tok), not total numbers https://stratechery.com/2021/mistakes-and-memes/
* _Pareto Principle_: power law, 80/20 rule i.e. minority constitute the most influential results https://macwright.com/2020/08/01/recently.html
* _Postel's Law_: liberal in what you send, conservative in what you accept
* _Zawinkski's Law_: every software will expand until it attempts to read email

## audit

🗄 `git.md`

ADR
* https://github.com/joelparkerhenderson/architecture_decision_record https://news.ycombinator.com/item?id=22694014 PEPs are ADRs https://www.python.org/dev/peps/pep-0518/ https://news.ycombinator.com/item?id=23915521
* https://matklad.github.io//2021/02/06/ARCHITECTURE.md.html https://news.ycombinator.com/item?id=26048784

changelog / release notes
* https://keepachangelog.com/ https://www.youtube.com/watch?v=Pi8akLplC9M
* https://github.com/nedbat/scriv
* https://drewdevault.com/2021/05/19/How-to-write-release-notes.html
* https://github.com/orhun/git-cliff

## diagrams

🔍 https://xosh.org/text-to-diagram/

types
* _ERD_: syntax https://eli.thegreenplace.net/2019/to-orm-or-not-to-orm/ 📙 Karwin [7] 🗄 `sql.md` utils
* _flow_: https://news.ycombinator.com/item?id=26303784
* _infrastructure_: https://github.com/mingrammer/diagrams 
* _state_: https://github.com/statecharts/statecharts.github.io/issues/44 https://en.wikipedia.org/wiki/State_diagram
* _tree/map_: https://github.com/niyue/skillmap
* _sequence_: msg passing https://sequencediagram.org https://gist.github.com/zachvalenta/2aeac1f945c5848c79087b2481cb187a
* _UML_: class diagram https://www.amazon.com/UML-Distilled-Standard-Modeling-Language/dp/0321193687
* can be used for ERD in Mongo https://stackoverflow.com/q/11323841 https://stackoverflow.com/q/6010408

providers
* ascii to SVG https://github.com/ivanceras/svgbob http://asciiflow.com/
* _DrawSQL_: ERD https://drawsql.app/me-195/diagrams/testing123
* _Excalidraw_: general https://excalidraw.com/ https://gist.github.com/zachvalenta/f4c2226b991b69d129fe7d1d40119f43
* _GraphViz_: all; https://sketchviz.com/graphviz-examples https://github.com/BurntSushi/erd
* _Mermaid_: all; editor https://mermaid.live/ no current Hombrew version https://github.com/mermaid-js/mermaid-cli https://github.com/mermaid-js/mermaid-cli/issues/25

## documentation

🗄
* notes
* `html-css.md` SSG

> Instead of a person being the source of truth on a subject, the document becomes the source of truth. https://benadam.me/thoughts/my-experience-at-amazon/
> Can I literally tell what your software is doing? - Atwood https://news.ycombinator.com/item?id=23676350

* durability policy https://vickiboykis.com/2021/07/17/writing-for-distributed-teams/
📍 quadrants https://www.thoughtworks.com/radar/techniques?blipid=202203016 https://news.ycombinator.com/item?id=26002656 https://documentation.divio.com/

gnostic
* https://news.ycombinator.com/item?id=30764505
* Python https://old.reddit.com/r/learnpython/comments/td653k/am_i_the_only_one_who_does_not_find_the_python/
> Unlike C++ and Modula-3, built-in types can be used as base classes for extension by the user. Also, like in C++, most built-in operators with special syntax (arithmetic operators, subscripting etc.) can be redefined for class instances. https://docs.python.org/dev/tutorial/classes.html
> So, to fix what I perceived as a flaw in Python's documentation, I set out to provide some more plain-English, example-driven documentation for Python's magic methods. https://rszalski.github.io/magicmethods/

culture of writing
* Stripe https://news.ycombinator.com/item?id=24725216
* Linux kernel https://lwn.net/SubscriberLink/885941/01fdc39df2ecc25f/
* != deliberation https://news.ycombinator.com/item?id=30361655 

alternatives
* https://github.com/vuejs/vitepress
* https://docsify.js.org/#/
* https://docusaurus.io/
* _GitBook_: https://www.gitbook.com/ https://rbspy.github.io/
* _mdBook_: Gitbook but OSS https://github.com/rust-lang/mdBook

MkDocs
* docs https://www.mkdocs.org/ https://squidfunk.github.io/mkdocs-material/getting-started/
* previous project https://github.com/zachvalenta/mkdocs-scaffold
* `docs_dir`: dir w/ documentation files; `docs` by default https://www.mkdocs.org/user-guide/configuration/#docs_dir
* `site_dir`: where built HTML goes https://www.mkdocs.org/user-guide/configuration/#site_dir
* `<head> <title>`: `site_name` https://www.mkdocs.org/user-guide/configuration/#site_name
* _image_: https://www.mkdocs.org/user-guide/writing-your-docs/#linking-to-images-and-media
* _video_: ❓ https://github.com/mkdocs/mkdocs/issues/243#issuecomment-208120665 https://developer.mozilla.org/en-US/docs/Web/HTML/Element/video https://stackoverflow.com/q/8885701
* Material: code block https://squidfunk.github.io/mkdocs-material/extensions/codehilite code inline https://squidfunk.github.io/mkdocs-material/extensions/pymdown/#inlinehilite highlight https://squidfunk.github.io/mkdocs-material/extensions/pymdown/#mark checkbox https://squidfunk.github.io/mkdocs-material/extensions/pymdown/#tasklist emoji https://squidfunk.github.io/mkdocs-material/extensions/pymdown/#emoji icon https://squidfunk.github.io/mkdocs-material/extensions/pymdown/#icons favicon https://squidfunk.github.io/mkdocs-material/getting-started/#favicon tabs https://squidfunk.github.io/mkdocs-material/extensions/pymdown/#tabbed footnote https://squidfunk.github.io/mkdocs-material/extensions/footnotes/ permalink https://squidfunk.github.io/mkdocs-material/extensions/permalinks/ note https://squidfunk.github.io/mkdocs-material/extensions/admonition/ dropdown https://squidfunk.github.io/mkdocs-material/extensions/pymdown/#details

Github
* have to create first page via Github https://stackoverflow.com/a/41423798 https://github.com/github/docs/pull/16468
```sh
# no first page
git clone git@github.com:zachvalenta/grok-dl.wiki.git  # access denied or repository not exported
```
* need to create own repo for wiki to get issues, PRs, etc. https://github.com/microsoft/vscode/wiki https://github.com/Microsoft/vscode-wiki
* file name conventions: `Home` (root) `_Siderbar` (file structure)
```sh
# git@github.com:zachvalenta/grok-dl.wiki.git
├── _Sidebar.md
└── Home.md
├── 01
│  └── one.md
├── 02
│  └── two.md
├── 03
│  ├── three.md
│  └── tres
│     ├── tres-01.md
│     ├── tres-02.md
│     └── tres.md
```
```markdown
**one**
* [[one]]

**two**
* [[two]]

**three**
* [[three]]
* [[tres]]
  * [[tres-01]]
  * [[tres-02]]
```

---

* accurate sources update frequently https://www.overcomingbias.com/2022/04/the-accuracy-of-authorities.html
* great docs: Rails https://api.rubyonrails.org/classes/ActiveRecord/Migration.html https://htmx.org/docs/
* more workplace liquidity = higher standards for docs https://www.drorpoleg.com/the-crypto-future-of-work/
* company idea as the one guy who does documentation https://news.ycombinator.com/item?id=27457860

* cog: Python cmd output to text file https://nedbatchelder.com/code/cog https://nedbatchelder.com/blog/202201/cog_resurgence.html https://til.simonwillison.net/python/cog-to-update-help-in-readme https://github.com/jostylr/literate-programming 🗄 `aesthetics.md` typography

* unit test to see whether something has docs https://simonwillison.net/2018/Jul/28/documentation-unit-tests/

https://benadam.me/thoughts/my-experience-at-amazon/
> PRFAQ - Press Release and Frequently asked questions: a document format used to pitch a new idea or investment opportunity
> OP1 - A team’s one-year business plan: what they are going to work on and try and accomplish
> BRD - A tactical plan for a particular project that lists all of the requirements in detail
> Design Document - An engineering document that lays out the technical strategy with a high level of detail, documenting the approach as well as alternatives considered
> 1 Pager - A summary document used to bring a stakeholder up to speed on a particular topic used for building alignment around goals

* customer service / help desk https://github.com/zammad/zammad
* https://simonwillison.net/2021/Sep/6/making-world-class-docs-takes-effort/
* documentation https://hynek.me/articles/document-your-tests/ more readable method signatures https://github.com/renanivo/pytest-testdox

* _slide decks_: worse than memos https://marginalrevolution.com/marginalrevolution/2020/08/against-slide-decks.html https://www.youtube.com/watch?v=7fIR55kkTwc
> I see a lot of organizations relying too much on slide decks relative to actual written memos for their internal communications. Presentations are great but prose has a unique value in clarifying thought and creating an unambiguous record. https://twitter.com/mattyglesias/status/1525107714904543234?cxt=HHwWhMC-8dzYoqoqAAAA
* _documentation_: note the confusing stuff https://news.ycombinator.com/item?id=22455678 immediate files https://the.exa.website/features/colours https://github.com/ogham/exa/pull/600 static site generators https://docusaurus.io/en/ https://readthedocs.org/ https://readme.com/ https://www.mkdocs.org/ sync code w/ README https://github.com/campoy/embedmd good docs https://github.com/benoitc/gunicorn/blob/master/CONTRIBUTING.md https://blog.garrytan.com/masterclass-with-algolia-how-to-capture-the-heart-of-20m-software-developers https://xkcd.com/378/ https://blog.pinboard.in/2019/07/i_cant_stop_winning/ https://www.google.com/search?hl=en&q=askew https://www.netmeister.org/blog/cs-falsehoods.html https://github.com/bup/bup#things-that-are-stupid-for-now-but-which-well-fix-later https://github.com/benoitc/gunicorn/blob/master/CONTRIBUTING.md
* _roadmap_: https://www.jibranelbazi.com/blog/what-is-a-product-roadmap https://about.sourcegraph.com/company/strategy#5-year-vision
* _todos_: https://github.com/preslavmihaylov/todocheck
* https://timilearning.com/

functions
> these taxonomy is for a service; have yet to consider impl for company https://about.gitlab.com/handbook/leadership/biggest-risks/
* raise d'etre: README
* install: README
* run: Makefile
* operate: https://man.sr.ht/ops/
* API: third-party docs site
* where to find everything else: README

pre-mortem https://about.gitlab.com/blog/2020/09/11/gitlab-pg-upgrade/

## project (PM)

🗄 `psychology.md` human factors

> I'm more interested in analysing organizational and market principles, and leveraging these theories to further reduce management work, rather than actually managing people https://news.ycombinator.com/item?id=27218751
* Grove, high-output management https://blog.danielna.com/starting-an-engineering-management-book-club/
* transparency https://about.gitlab.com/handbook/ https://about.gitlab.com/handbook/leadership/biggest-risks/

* questions for mgmt role https://jacobian.org/2019/apr/23/questions-for-employers-director-vp/
* _principal-agent problem_: conflict in interest btw principal (person for whom action is taken e.g. voters) and agent (person taking action e.g. politician) 📙 Fukuyama origins 308 https://betonit.substack.com/p/blame-the-principals
* _zero-based budgeting_: throw out last year's budget; 3G Capital, Buffet

* retrospective: rose/thorn/bud

mgmt is easy
> Becoming an L5 manager in a big company is supposed to be a considerable challenge. But unless you're an idiot, it will be the easiest job you ever have. All you have to do is plug yourself into the calendar and set your brain on autopilot. Go to the meetings you're supposed to go to, say the acronyms you're supposed to say, update the spreadsheets you're supposed to update, and don't do anything that may compromise the system. https://www.spakhm.com/p/parallel-tracks
> you must understand that KPIs, OKRs, meetings, and company values are just performative rituals. https://www.spakhm.com/p/how-to-get-promoted
> Since the overt objectives are merely performative, you need to determine your actual objectives. Fortunately they're the same in every growing company, so you don't need to do any detective work to discover what they are. Your primary objective is simple— headcount growth ("do a lot with a little" is another shibboleth, don't take it literally).
> Don't worry about what all these people will work on. The devil will conveniently find work for idle hands. Expanding companies never have a shortage of business opportunities, projects, and tasks. The work will invent itself. Your job isn't the work— it's to grow headcount and make it appear well-managed. That latter part is nearly entirely performative. Look at other teams that are considered well-managed and emulate the trappings. Usually that means lots of meetings, cross-functional collaboration, document writing, one on ones, performance reviews, and agile. You will need to ship things, but not that much. By the time any of this gets objectively evaluated, you'll be happily working in a different role, and someone else will deal with the objective metrics.
> Feigning sincerity in a convincing way is extremely difficult. So if you take any of this career advice, it's best to learn to candidly believe it.

issue tracking
* ticketing creates overly technical solutions https://news.ycombinator.com/item?id=25516125
* _Jira_: workstream (project) initiative (component) epic (functionality) labels (hgx-label-# brown, orange, yellow, light blue, dark blue, green, mauve, purple, pink) JQL for search
* Linear https://news.ycombinator.com/item?id=23693029
* https://github.com/mattermost/focalboard
* https://thorstenball.com/blog/2017/01/16/what-i-didnt-do-to-write-a-book/

misc
* project owner (why) project manager (what) https://news.ycombinator.com/item?id=25288133
* project management is for doing something new, not keeping the lights on https://www.arnoldkling.com/blog/vaccine-distribution-and-the-obamacare-web-site/
* GTD https://www.newyorker.com/tech/annals-of-technology/the-rise-and-fall-of-getting-things-done
* slow down https://blog.cerebralab.com/Encouraging_the_Wrong_State_of_Mind_for_Creating_Good_Code

https://cloud.google.com/solutions/devops/devops-culture-westrum-organizational-culture
* Paypal as Netflix predecessor http://paulgraham.com/paypal.html
* https://www.martinfowler.com/bliki/OutcomeOverOutput.html https://www.martinfowler.com/bliki/WaterfallProcess.html
* people choose technology to improve their resumes https://news.ycombinator.com/item?id=22496245
* https://increment.com/teams/
* most people use Jira to do waterfall, there's always a yearly roadmap deck and the epic/initiative/<term> start cascading from there
* https://almad.blog/essays/no-bugs-just-todos/
* proliferation (Monday, Basecamp, et al.) https://softwareengineeringdaily.com/2020/03/20/clickup-engineering-with-zeb-evans-and-alex-yurkowski/
* https://jacobian.org/2021/jan/5/designing-engineering-organizations
* _tools_: Asana, Atlassian, Trello, Github issues https://blog.codepen.io/2016/05/10/089-knowledge-management/
* _approaches_: agile (small, frequent, working releases) kanban (limit WIP https://www.youtube.com/watch?v=HHOkcCqsipE https://news.ycombinator.com/item?id=32910352) scrum (PM framework) chief programmer https://en.wikipedia.org/wiki/Chief_programmer_team
* _XP (extreme programming)_: hill-climbing 📙 Evans domain-driven [xxiii]
* _scrum master_: person that pretends to know wtf is going own and lapdogs for business
* _dev team_: lurching from sprint-to-sprint at the summons of business; responsibility w/out power
* _Zey_: unspecific mtg (sync, open-ended KT) verbalizing the trivial as a child (I'm hungry, I'm sleepy) doesn't listen, one-upper "party A: that was hard LEADER: you think that's hard? let me tell you about..."
* _sink_: https://www.lambdacambridge.com/blog/how-scrum-disempowers-developers-and-destroys-agile https://medium.com/@jsonpify/you-dont-need-standup-9a74782517c1 https://medium.com/@bellmar/people-hacks-for-technical-leads-6eef1576d046

choosing the right problem dominates execution speed
> The SWE3 may spend his time writing a bunch of unit tests that catch bugs that wouldn't really have happened anyway, or migrating from one system to another that isn't really a large improvement, or going down an architectural dead end that'll just have to be rewritten later. https://danluu.com/hn-comments/#what-makes-engineers-productive-https-news-ycombinator-com-item-id-5496914 https://danluu.com/p95-skill

don't go overboard on planning
> So if you spend a lot of time planning in advance, what you'll end up with is a minutely detailed plan for solving the wrong problem.

kanban can be an anti-pattern https://techcrunch.com/2018/12/09/jira-is-an-antipattern/
> Worst of all, though, is the endless implicit pressure for tickets to be marked finished, to be passed on to the next phase. Tickets, in the JIRA mindset, are taken on, focused on until complete, and then passed on, never to be seen again. They have a one-way life cycle: specification; design; development; testing; release. Doesn’t that sound a little...um...waterfall-y? Isn’t agile development supposed to be fundamentally different from waterfall development, rather than simply replacing one big waterfall with a thousand little ones?

fundamentally unserious about engineering culture
> Startups spend a lot of time thinking about growth, and while they'll all tell you that they care a lot about engineering culture, revealed preference shows that they don't. With a few exceptions, big companies aren't much different. At LCB, I looked through the competitive analysis slide decks and they're amazing. They look at every last detail on hundreds of products to make sure that everything is as nice for users as possible, from onboarding to interop with competing products. If there's any single screen where things are more complex or confusing than any competitor's, people get upset and try to fix it. It's quite impressive. And then when LCB onboards employees in my org, a third of them are missing at least one of, an alias/account, an office, or a computer, a condition which can persist for weeks or months. The competitive analysis slide decks talk about how important onboarding is because you only get one chance to make a first impression, and then employees are onboarded with the impression that the company couldn't care less about them and that it's normal for quotidian processes to be pervasively broken. LCB can't even to get the basics of employee onboarding right, let alone really complex things like acculturation. This is understandable -- external metrics like user growth or attrition are measurable, and targets like how to tell if you're acculturating people so that they don't ignore weak signals are softer and harder to determine, but that doesn't mean they're any less important. People write a lot about how things like using fancier languages or techniques like TDD or agile will make your teams more productive, but having a strong engineering culture is much larger force multiplier. - https://danluu.com/wat/

## search

🔍 query https://www.gnod.com/search/
* general: DuckDuckGo https://github.com/jarun/ddgr Google https://github.com/jarun/googler
* dev: Stack Overflow, tldr
* randon: Wolfram https://www.wolframalpha.com/ https://news.ycombinator.com/item?id=29131931
* intellectual: MR, BlogSearch https://news.ycombinator.com/item?id=30844149 Marginalia https://search.marginalia.nu

📚 reference
* notes
* bookshelf / fs
* Wikipedia

🖼 context
* Youtube
* In Our Time
* dev: HN, awesome-<tech>, SED, Running in Production
