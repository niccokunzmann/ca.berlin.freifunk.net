Contributing Guidelines
=======================

This should guide you through your contribution.
Please note that this document is never complete and you can contribute to it to make it better.

Issues
------

If you want to change something but you are not entirely sure how to go about it, please open a [issue]
to discuss it.

Pull Requests
-------------

Please reference the issue in the pull request. This way we keep track of what belongs together.

Commits
-------

The commit messages allow us to track the problems solved and the solutions taken.

Please write commit messages which summarize the change and the file in the first line.
You can reference issues. E.g. You can reference issue number 54 using [#54] and it turns up as a link, see below.
After an empty line, please add a more to know about the change.

See this [example commit]:

> requirements.txt: update psycopg2 to 2.7.3.2
>
> this brings pg10 support
> and probably fixes  Travis error ```Error: could not determine PostgreSQL version from '10.1'``` seen in PR [#58]

Testing
-------

Test should run before the change is used.
You can help by updating your branch with the master branch.

[issue]: https://github.com/freifunk-berlin/ca.berlin.freifunk.net/issues
[example commit]: https://github.com/freifunk-berlin/ca.berlin.freifunk.net/commit/6f129b673d8a7a24ed6293610b58c7fc091767ac
[#54]: https://github.com/freifunk-berlin/ca.berlin.freifunk.net/issues/54
[#58]: https://github.com/freifunk-berlin/ca.berlin.freifunk.net/pull/58
