# 136 facts every web dev should know before they burn out and turn to landscape painting or nude modelling

https://www.baldurbjarnason.com/2021/100-things-every-web-developer-should-know/

Everything I’ve learned about web development in the almost
twenty-five years I’ve been practising. All boiled down into a
neat little list that I put together over a week.

I’m Icelandic, so I’m prone to absolute statements. It’s a cultural thing.

No, I’m not going to explain any of these.

-   There are exceptions to most rules.

-   Web development becomes more complicated the more you pull it
    apart and less so the more you step back.

-   The best way to improve software UX is regular direct
    observation, by everybody on the team, of the work done.

-   Software development needs to support the needs of those in
    the organisation. Otherwise, its ability to serve the needs of
    the customer will fall apart in short order.

-   You may think that software development at a software company
    serves the customer directly, but you’d be mistaken. The
    organisation is the software development team’s primary
    customer.

-   One of the biggest problems in web development, specifically
    and software development in general, is
    [failure demand](https://vanguard-method.net/failure-demand/).
    [“Failure demand is demand caused by a failure to do something or do something right for the customer."](https://vanguard-method.net/library/systems-principles/failure-demand/)
    (John Seddon, 2003).

-   Examples of failure demand in software development:

    -   Having to rewrite code because, while you fulfilled the
        documented requirements, you didn’t meet the
        organisation’s actual needs.

    -   Having to spend all your time fixing bugs. Your sole focus
        at the start of the project was delivering features. Now
        you don’t have time to do your work cleanly *without
        creating bugs* because all your time goes into fixing
        them.

    -   Building the wrong product because you didn’t understand
        the needs of the customer.

    -   Spending all your time deploying or testing by hand
        because you never spent time on automation.

    -   Having to redo a feature because the spec was unclear.

    -   And more.

-   Most software projects consume 5x, 10x, 20x more resources
    than they should because failure demand consumes most of the
    organisation’s resources.

-   HTML is fantastic. Even if you can do a task without it, keep
    using HTML to manage, update, or encapsulate your CSS or JS
    work. (Custom Elements!)

-   Everybody has small screens, and they all know how to scroll:
    only make UI widgets ‘sticky’ or ‘fixed’ if you have to. They
    know where your navigation bar is. You don’t have to push it
    in their face the whole time.

-   Everybody has small screens, and they all know how to scroll:
    make sure that what they see when the page loads tells them
    there is something below the fold. They will scroll down if
    they have the slightest reason to. If only to see how dumb
    your work is.

-   Everybody has small screens, and they all know how to scroll:
    scroll position is a part of the application’s core
    state. Preserving scroll position across navigations is an
    easy UX win.

-   If the user has big screens, make use of them. When you have
    space, opt for detail over decoration, data over branding,
    buttons and navigation over menus.

-   Sturgeon’s law applies to your work as well. Don’t linger on
    one project forever. Make new things. That’s the only way to
    learn.

-   The trick is to recognise when it’s time to move on.

-   A visitor to your site begins by building a map of it in their
    heads. Because without that internal map, nothing they will
    ever do on your site will fully make sense to them because it
    has no context.

-   Context is essential.

    -   Show them what you got, yes, but show it to them in
        context.

    -   Visible context is always preferable to the context that
        has been shuffled off into a hidey-hole somewhere.

    -   See above about using the big screen if you have it.

-   Use multiple screens if you can. The web is hypertext. Your
    app can exist on anything that can load an URL over HTTP. Try
    and do something useful with it.

-   Have some personality: web dev is a pop culture and rewards
    personality. It doesn’t necessarily reward originality or
    quality but, as long as you don’t let us down elsewhere, it
    does reward having character.

-   Have some personality:

    -   MID (Medium-Inspired Design) is mediocre.

    -   Everything looks the goddamn same. Same sans serif
        fonts. Same flat illustrations. Same colour
        schemes. Same. Same. Same.

    -   You can get away with looking boring if something else
        about your work is inventive but not if the whole thing
        you’re doing is by-the-numbers.

    -   Even if what you’re making is original, why not look
        memorable while you’re at it?

-   Most products don’t need the features that SPAs provide. Teams
    need SPAs but not for the product itself. SPAs make for great
    demos and lovely presentations, which leads to more support
    for the team, more funding, and that way, SPAs improve the
    odds of success.

-   Then SPAs take away what they give because they are
    error-prone and costly to develop. So much state to track. So
    many built-in features to reimplement.

    -   The first rule of SPAs: we always underestimate the
        complexity of handling state. Often by a large margin.

    -   The second rule of SPAs: we always underestimate the
        complexity of reimplementing history and link
        navigation. Often by a large margin. But we get away with
        not caring because nobody tests history management
        properly.

-   SPAs are too much work: take the time and money you’d spend on
    SPAs and frameworks and spend it on the UX design
    instead. SPAs aren’t necessary for good UX design. Animation
    and swishy transitions aren’t good interactivity
    design. (“Design is how it works.") Which reminds me.

-   Every SPA I’ve ever used has at some point let me down when it
    comes to navigation or history management:

    -   Resetting a view when you click the back button (browsers have an excellent back-forward cache! Use it!).

    -   Not loading the correct view.

    -   Failing to load a part of the screen.

    -   Losing data/context when opening a link in a new tab.

    -   Or just giving up altogether.

    -   They all fuck up at some point. Server-routed sites aren’t
        perfect, but there’s a lot less that can go wrong.

-   Every SPA breaks the back button in some way. Often it won’t
    let you ‘back’ out of a site, where it always redirects you
    forward again whenever you hit the initial page that sets
    everything up. Other times it’s a more subtle error, but they
    all break it somehow.

-   Design is what we do. Design is what the user does. Design is
    our actions that result in a field of possibilities for the
    user. The web is an interactive medium. If it isn’t something
    done by somebody – the digital embodiment of an action
    somebody has taken – then it is garbage, and you should do
    away with it.

-   Minimalism is garbage. Simplicity is great, but minimalism
    sucks. Everything you see on the screen should have a reason
    to be there (be an embodiment of ‘doing’), but if the reasons
    are complicated, then the design should represent that
    complexity. Hiding complications makes everything harder, and
    excessive minimalism is just as harmful as excessive
    decoration.

-   Data processing is not a complication. That can safely be
    shuffled off into the background or behind an abstraction.

-   Complication is something involved that the user has to be
    aware of or do. If it’s something to be automated or handed
    off, then you still can’t get away with hiding away.

-   Feedback loops are what interfaces run on, and hiding details
    away is a surefire way of breaking a feedback loop.

-   Decoration is like junk food. It’s great in moderation. A
    little bit here and there is necessary to give life colour and
    vividness. But too much of it will kill you.

-   You still need some decoration. See ‘have a personality’
    above. But not as much as you think because—

-   It isn’t decoration if it changes the ‘doing’. When it frames
    something and changes its meaning, it’s a frame (parergon if
    you’re a Derrida fan).

-   It isn’t decoration if it changes the ‘doing’. Styling Tetris
    so that it’s now a game about stacking bodies in a mass grave
    isn’t decoration but design. Horrifying, but still a design.

-   Metaphors are fantastic. When you combine them with thoughtful
    visual design, they can transform a by-the-numbers web service
    or app into something groundbreaking.

-   Naming things is fantastic. Everything on the screen should
    have a name. It’s better for your work. It’s better for
    accessibility. It’s better for your design. Take a table view
    and name it ‘Inbox’, ‘Screener’, or ‘Paper Trail’, and they
    suddenly mean something. What you do with them has changed. A
    good name transforms design and action.

-   Prefer HTML over CSS over Images over Typefaces over
    JavaScript, in that order. Roughly.

-   Don’t be mean. Make sure that undo works. And don’t get hung
    up on complex computer science. ‘Undo’ in this context means
    ‘can I make it right if I do something I immediately regret?’
    Put a slight time delay on the action. Fake those deletes for
    a few hours. Every update should preserve the version you are
    replacing somewhere, even if it’s only in this one tab on this
    one device. That way, you can give them one level of
    undoing. They already regret having to use your app; don’t
    make them regret you were ever born. (Too late! Hah!)

-   Use URLs, links, and hypertext. Try not to hardcode
    relationships or URLs.

-   Use URLs from links with rel values over URLs in attributes
    over URLs in properties over URLs in source code. Do it in
    that order. Apply that to anything that speaks HTTP in your
    app.

-   Try to write HTML that would make sense and be usable without
    the CSS. Not because you ever expect that to happen
    (**cough**reader modes**cough**) but because that way you get
    a ton of freebies: appropriate default styles and built-in
    default behaviours. HTML-first means less work overall, both
    in styling and interactivity, because you start by seeing how
    much work HTML can provide before you step up to other layers.

-   Try to write HTML that works and is usable without JS. Not
    because you ever expect that to happen, but because that way
    you get a ton of freebies: built-in input validation, form
    submission through a variety of input modes, UI widgets that
    are accessible out of the box, link navigation that fully
    supports the options the user’s OS provides.

-   Try to write your CSS in layers.

    -   A settings stylesheet that collects all of your base
        variables.

    -   A base stylesheet that serves as the foundation.

    -   Layout stylesheets. Each one should implement a layout or
        composition without depending on other stylesheets.

    -   Block stylesheets that are the motif to your composition,
        the phrases in your structure, the recurring themes of
        your design.

    -   And the utilities that do one thing and one thing only.

-   Load your styles *in that order*. Your utilities should
    override your motifs, your motifs should override your
    compositions, your compositions should override your element
    styles, and the variables from everything else should override
    your default variables. Use the cascade, Luke! Use the
    cascade!

-   Style JS-driven state using ‘data-*’ attributes, style app
    design using classes, and style defaults using elements. Don’t
    let JS drive classes if you can help it. And don’t set style
    defaults using the class attribute.

-   Only target CSS with the ID selector as a last resort. IDs are
    already used by JS, ARIA attributes, link navigation, input
    labelling, and more. Even without specificity issues, the ID
    attribute would be too overloaded, too tightly coupled to
    other layers in the web stack, to be anything but trouble.

-   Only use the ID selector in your CSS as a last resort to fix
    extreme and hard-to-solve specificity issues. Try doubling up
    on a class first. `.class.class` is a valid selector and can
    work wonders.

-   A specificity problem that’s hard to solve without
    `!important` usually means you haven’t thought through the
    structure of your CSS. Reaching for that `!important` instead
    of refactoring means you’re letting your CSS rot: technical
    debt is piling up.

-   Because of the cascade, CSS is more sensitive to structure
    than most other code. You probably should refactor your
    stylesheets more often than you do your JS.

-   Add IDs to every landmark and every paragraph if your tools
    let you. It’s rare to find a widely supported API that is
    usable by a broad section of the population. Links with
    fragment selectors are one of them. But to make them work,
    your HTML needs to have IDs.

-   Make the problem browser your development home. If Firefox
    always gives you pain, live in it. Make it your work
    browser. Almost all of your Firefox-specific problems will
    disappear because you end up fixing them as you go, without
    thinking. Tight feedback loops are magic.

-   The only exceptions to this are the mobile browsers because
    mobile OSes are garbage. They don’t let you do any real work
    or development. Maybe they work for you. Great for you. But
    the inflexibilities of mobile OSes mean that they just can’t
    serve the variety that desktop OSes do. Which means that—

-   Mobile websites are always going to suck. They’re going to
    suck for development. They are going to suck for users. We can
    put in the work to make sure they don’t suck for the user, but
    that just means they suck extra hard for us.

-   Tight feedback loops are magic: live reloading is magical. Hot
    module replacement less so. With live reload, your development
    browser automatically reloads your dev page when your code
    changes. If you suck and your page loads slowly, then you
    suffer. Hot module replacement hides the pain and lets you
    pass the suffering onto the user.

-   Tight feedback loops are magic: build processes suck. They
    will always suck because they always loosen up the feedback
    loop. You can make builds quicker, but until they are
    virtually instantaneous, they will always suck. (Which could
    happen. *waves towards esbuild*.) If you can make something
    without a build step, do so. If you can make something without
    compilation or building, do that.

-   Svelte and Typescript are very useful, but the cost of
    building is always more than you think, especially once the
    codebase grows.

-   JS building adds the most value when you have many
    dependencies. In that case, it’s essential. But if you have
    few to no dependencies, most of the caveats about not building
    your JS go away. If you find yourself in that position: skip
    the build.

-   Dependencies suck; dependencies rule. Other people’s code is
    like getting other people’s work for free. The downside is
    that it comes with their opinions, hobbies, and hygiene
    attached. All code comes bundled with a code smell. Usually,
    there isn’t anything you can do to prevent it from stinking up
    the place.

-   Every dependency you use has security issues: if you don’t
    check them all to see if their issues are ones you can live
    with, then you’re probably going to pay for it later.

-   Sometimes, the best thing an open-source project can do is
    demonstrate how you solve a problem. Adding it as a dependency
    afterwards is often a huge mistake.

-   The job of development is to build a theory in your mind about
    the codebase.

-   Too many dependencies can make that harder, not easier. Having
    too many dependencies can obfuscate the work that you are now
    having done for you by proxy.

-   The developers' mental model of the codebase is what keeps it
    alive.

-   DRY (don’t repeat yourself) is a luxury for when you have a
    coherent theory in your mind of the app’s code.

    -   It’s for when you have that theory contained in a
        worldview in your mind that helps you quickly test out
        decisions and plans against that theory.

    -   Until then, you should repeat yourself. Seeing your code
        repeat itself – when rhyming phrases start to pop up
        throughout – is a vital tool for building a theory about
        your app.

-   Avoid using web workers (the web stack’s equivalent for a
    process) or threads if you can. They make theory-building
    harder. Only use them when they can be wrapped in a nice
    metaphor and modelled as standalone services or isolated
    functions, like a service worker or an unzip utility.

-   Dependencies can sometimes do what you would never do, use bad
    ideas, take risks you never would. At least that way, when
    something blows up, you have someone else to blame.

-   Of course, you chose to add the dependency, so either way, you
    are responsible.

-   Despite what you may think, offline-first isn’t
    essential. It’s a lot of work, changes everything you make in
    the app, and, while everybody loves it when they need it,
    almost nobody will pay for it. Given two options, the odds are
    that buyers will buy the one that doesn’t support
    offline. (‘Buyer’ here being anything from an end consumer to
    an in-house stakeholder.) Why? Because it’s almost certainly
    cheaper and more reliable in a highly connected environment.

-   The buyer is quite often wrong. That fact never changes their
    mind.

-   Working on a functioning app’s codebase does more to increase
    its quality than adding features.

-   Managers will always undervalue plain old code work.

    -   Working on an iffy codebase (and they all start iffy) to
        make it cleaner, more sensible, and more robust without
        adding features or functionality can save you weeks if not
        months of future work.

    -   Once you have a working app, working on code quality is
        just as likely to provide as much business value as a new
        feature.

    -   Managers will never, ever, ever be able to see or
        understand this.

    -   But a good manager doesn’t have to because they will give
        your team the autonomy to do things they don’t
        understand. A good manager will trust that you are working
        to address the organisation’s needs (and the needs of
        those in it) without arguing with you.

-   A good manager *will* debate you, and that’s awesome.

-   Fuck ups happen. Nobody is to blame even when somebody is
    responsible. Use it as an opportunity to see where the process
    didn’t work. And if you don’t have a process—well, that’s
    what’s wrong. Right?

-   Fuck-ups happen. The run-up to the fuck-up is more interesting
    than the fuck-up itself. How did it happen? What made it get
    this far? Why didn’t anybody speak out sooner? Why didn’t
    somebody try to help sooner?

-   Fuck-ups happen. Some people make it their mission in life to
    make sure that whenever a fuck-up happens, somebody will
    suffer. Don’t be that person, and don’t let that person get to
    you. They’re an ass.

-   Fuck-ups happen, but they don’t always have to: a checklist
    does wonders. No, really. It will save your ass even without
    automation or coding.

-   Every manager has an inappropriate love that will make life
    miserable for their reports. Some love meetings but will
    rarely put in the work to make those meetings worthwhile. Some
    love email but are incapable of putting together a coherent
    sentence.

-   Prefer structured communications tools like an in-house blog,
    a wiki, Basecamp, Notion, or GitHub over unstructured
    messaging platforms like email or Slack. Your work has
    structure; so should your communications.

-   Don’t rely too much on tools. They will let you down.

-   Digital publishing is, for the most part, just a bunch of
    unrelated business models wrapped up in an exterior layer of
    design metaphors. Without the metaphors, it’s just sparkling
    websites.

-   We have already baked in all of the downsides of XHTML into
    all of our dev tools. They tend to be stricter and more
    fragile than XML ever was and require you to use a pseudo-,
    often home-baked, markup format (*cough*JSX*cough*) that
    breaks just as often. Meanwhile, XHTML has semantic
    extensibility and native CSS support for extension
    namespacing. Both natively implemented by the browser. Not
    saying we should all switch back to XHTML (browser support is
    still there!) but I *am* saying XHTML had a lesson to teach
    us, but we didn’t pay attention and haven’t learned a thing.

-   In other words: web dev is a pop culture with no regard for
    history, dooming each successive generation to repeat the
    blunders of the old, in a cycle of garbage software, wrapped
    in ever-escalating useless animations, transitions, and
    framework rewrites.

-   The term ‘project’ is a poor metaphor for the horticultural
    activity that is software development.

    -   Some software is seasonal and has crops, but unless you
        want your business to end with the first harvest, you need
        to treat it like a living ecosystem.

    -   Some software components are perennial and
        evergreen. Others are seasonal and need regular
        replanting. The project metaphor treats them both the same
        and increases the risk of code rot.

-   “Project management” is often used as a label for the somewhat
    helpful tools we use to organise work. Don’t let the project
    metaphor lead you to misuse these tools or to disregard them.

-   Most project management software is garbage because
    organisations generally don’t lack the tools to manage
    work. You could replace most project management software with
    a spreadsheet with no issue. The problem all organisations
    have, which most think is a project management problem, is
    team and organisation communications.

-   You can get away with simple management tools and tactics (a
    whiteboard and a spreadsheet) if your organisation has good
    trust and communications. Most *don’t*, however.

-   Most ‘innovative’ tech startups face what I like to call ‘the
    clear field problem’. Whenever you have an app or business
    idea that nobody else seems to have done successfully before,
    it’s never because you are particularly clever or
    original. It’s always because everybody else who has tried is
    now dead in a ditch somewhere (metaphorically speaking).

-   The only exception to this is when a brand new technical
    innovation opens up a new field. Which is rarer than you think
    as a better design doesn’t qualify as sufficient
    innovation. Unless you are the one who spent years developing
    that innovation from scratch, you are only performing
    arbitrage. That’s a recipe for squashed margins and brutal
    competition.

-   If you’re lucky, the first-mover advantage will save your
    ass. The odds are against you, though.

-   Some fields, when unregulated, will inevitably get dominated
    by a monopolist or an oligopoly. Monopolies are never the good
    guys. Don’t aspire to become one.

-   Any field with multiple successful competitors is good
    news. It means that there is demand, which you can tap in by
    addressing the problem in your way. In a sector with solid
    margins, this is an opportunity for design innovation to
    shine.

-   Any field where all of the other competitors are free
    services, outdated desktop apps, open-source communities with
    no revenue, or wannabe startup cults burning through cash is a
    lethal minefield covered in a cloud of mustard gas.

-   Never go up against a free service from a multinational. At
    least, never directly.

-   Try to position yourself so that the free services from other
    companies complement your paid service.

-   Try not to couple your service tightly with one provided by a
    multinational (free or paid). Almost all software is
    garbage. The problem with other people’s software is that they
    (justifiably) don’t care if it’s breaking your stuff.

-   One (possible) exception is when you are an actual paying
    customer. Build your business on AWS by all means but be wary
    of making Google Docs the foundation of your service.

-   You are occasionally warned against building an app that
    should just be a feature of some other app or service. This
    advice is unhelpful. Apps with limited scope that interoperate
    through shared file formats (usually text, sometimes images)
    are a great productivity enabler.

-   What you should avoid is building apps that are complements to
    other, more successful services. That applies to direct ones,
    like plugins or extensions, and indirect ones like EPUB
    reading apps. All the money, power, and control is in the
    other service, which is a recipe for a miserable time.

-   Counter-intuitively, the same type of app can complement or be
    standalone depending on the *file format*. An EPUB reader is
    almost always a support function for either an ebook library
    service or an ebook retailer, as those are pretty much the
    only ways people use EPUB files. A PDF reader, however, can be
    a sustainable business because the file format is a
    commodity. Anybody can make one. Anybody can read one. It’s
    used everywhere and by everybody.

-   Commonly used file formats with robust ecosystems enable
    software diversification as no single tool has to solve all of
    the problems.

-   HTTP, links and URLs are powerful, even if you aren’t working
    with HTML or JSON.

-   Web software is generally rubbish. You can explain this, at
    least partially, by the dominance of APIs over file formats in
    web tech circles.

-   A service that requires a new file format is going to have a
    hard time. It’s going to have an even harder time if it is
    competing with a service that works with standard file
    formats, even when the former is objectively better for the
    problem at hand.

-   Your service will have difficulties competing if it expects
    its API to solve the same problems for its users as a standard
    file format would.

-   Any field where all of the other competitors have five (or
    more) salespeople for every developer isn’t going to be
    pleasant for the developer, no matter if they’re an employee
    or a founder. Probably great if you’re a salesperson, though.

-   People lie when you do research. Watching what they do for an
    hour will tell you more than a hundred hours of interviews.

-   People lie when you do research but pay attention to the tools
    they reach for, the pains they describe, because those can
    reveal threads you can pull on to unravel your way to the
    actual problem. It takes practice, though.

-   Web dev is pop culture. Don’t get too stuck on
    trend-du-jour. Give it enough time and what was old is new
    again.

-   Web dev is pop culture. You have two choices: keep up with the
    trends or have enough individuality to be timeless. (Which is
    easier said than done, though.)

-   Web dev is pop culture, and managers have no taste. Most
    managers have no taste or judgement of their own when it comes
    to web development. The only tools they have to assess web dev
    are current trends and fashions in web dev pop culture. There
    is nothing you can do about this. Try to either find a manager
    with taste (rare!) or find one that trusts their developers to
    do the job despite not understanding the details.

-   Trust is a recurring theme when it comes to teamwork. Clear
    communications and trust will smooth over a lot of fuck-ups.

-   A solid business model will smooth over a lot of fuck-ups. You
    can get away with a bit of mismanagement if your margins are
    big enough.

-   It all comes down to needs. If an organisation isn’t
    addressing the employees' needs, nothing in the organisation
    will be sustainable in the long term.

-   Your needs come first. Then come those of your
    co-workers. Both come before that of the customer and before
    that of your manager. You need to be healthy, learning about
    the task at hand, improving your mental model of the product,
    and building a theory of how the code works. Otherwise, you
    aren’t going to be able to address anybody else’s needs.

-   A good manager will structure the organisation and processes
    so that the workers' needs, when fulfilled, will result in
    them being able to meet the customer’s needs.

-   A bad manager will churn through employees like tissue paper,
    sacrificing their well-being for vague and distant business
    goals.

-   The worst manager sacrifices their well-being as well as their
    employees' well-being.

-   As Deming said: [‘nobody gives a hoot about
    profits’](https://deming.org/nobody-gives-a-hoot-about-profit/). The
    manager who cares about company profits doesn’t exist.

-   A manager who seems to care about company profits is more
    dangerous than most. They are suffering from one or more
    psychological complication.

    -   “If the company does well, then I’m a good person.”

    -   “If we make money, then my mother will be proud of me.”

    -   “My dad—I mean the CEO—thinks I’m great.”

-   A lack of self-awareness is always trouble. In yourself, it
    causes misery. In a co-worker, it causes tension. In a boss or
    manager, it spells disaster. The only person you can send to
    therapy is yourself. The rest require firm boundaries and
    [non-violent
    communication](https://en.wikipedia.org/wiki/Nonviolent_Communication).

-   The web enables remote work. That doesn’t mean work in
    isolation. Pick your people. Choose your society.

-   The web exists in many forms, all of them valid in some
    context. Sometimes SPAs are the right solution. Native apps
    can use parts of the web stack and use them
    well. Understanding each medium is the key to understand the
    form you have chosen. Each form lends itself to specific
    actions. [The medium is the
    message](https://en.wikipedia.org/wiki/The_medium_is_the_message).

-   Most of the *major* web dev innovations over the past decade,
    at least, are optimisation functions designed to help
    dysfunctional organisations extract value from open source
    without blowing up. They serve to gloss over communications
    problems, subsidise training, offload recruitment costs onto
    somebody else, make it easier to collaborate on problems that
    aren’t actual problems. They help implement ideas that
    probably shouldn’t become a reality. All to suck value that
    ultimately was created by open-source software.

-   Web dev frameworks are for organisations, not small software
    teams or individual developers. The value frameworks provide
    lies in bridging team boundaries: they create a shared
    understanding that aids in collaboration across groups,
    simplify messaging, and establish clear
    conventions. Frameworks turn teams in large organisations into
    service interfaces.

-   Individual teams or individual developers don’t have that
    problem, so they get less value from a web dev framework. The
    more opinionated the framework is and the more of the web
    platform it abstracts away, the more its value proposition
    skews towards solving organisational problems and the less
    value it provides to individual teams.

-   None of this applies to learning. Having experience using
    frameworks can be extraordinarily useful. Being able to use
    the powerful capabilities of the platform itself is also an
    advantage. Individual needs and priorities vary too much. The
    above framework heuristic isn’t always correct.

-   Some tools feel more natural than others. Others remain opaque
    as hell. Which tool is which will vary from person to person,
    age to age, job to job.

-   Sometimes it’s rewarding to work with a tool that clicks for
    you, gets you into that flow to just get things done.

-   Sometimes the most rewarding thing to do is to work with a
    tool that *doesn’t* click, is hard as hell for you to
    understand, and feels like a never-ending slog.

-   Sometimes all you need is a single web page with no
    interactivity.

-   Sometimes deliberate complication is just plain fun, and that
    has value in and of itself.

-   You could replace most web services and apps with a blog,
    wiki, forum, or spreadsheet. Your service needs to be much
    better.

-   You could replace most web services and apps with a pen and
    paper. All forms of productivity, writing, or organisation
    software compete directly with pencils, notepads, and
    post-its. And those are amazing. They work offline, don’t need
    power, never need rebooting, are robust as hell, and cheap as
    chips. They also have decades or centuries of history. You
    need to either be 100x better or to enable activities that
    aren’t possible otherwise.

-   Just because you did something to make the impossible possible
    doesn’t mean that it’s worthwhile or that anybody
    cares. Society has no obligation to reward hard work or new
    invention. Just because you made it possible doesn’t mean it’s
    sensible.

-   Making the complex simple also isn’t worth anything in and of
    itself. What is worthwhile is when you encode knowledge,
    skills, and practices into an interactive design and make
    something that’s rare and exclusive, distributed and
    accessible.

-   You could say that this is the contribution the web has made
    to the modern world that has had the most impact: things that
    once existed in isolation are now widespread and
    accessible. Connecting and conveying is the web’s killer app.

Things I didn’t have time for:

-   Reed’s law and Metcalfe’s law don’t mean what you think they
    mean.

-   The germ theory of management.

-   How most managers think that ‘autonomy’ means the freedom to
    do whatever you want as long as it’s what they think you
    should be doing.

-   There’s no silver bullet.

-   Alan Kay’s ‘doing with images makes symbols.’

-   Wiki’s aren’t what you think they are. (All note-taking apps
    will grow until they contain an ad-hoc, haphazardly designed,
    poorly-thought-out reimplementation of a wiki.)

-   Ted Nelson didn’t say what you think he said.

-   Lessons from Hypercard (cards, stacks, plus links is a
    fantastic conceptual model for hypertext design)

-   Lessons from Flash (a timeline metaphor plus symbols and
        actions is a fantastic conceptual model for interactivity
        design).
    
