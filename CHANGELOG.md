# Change Log

## [Unreleased](https://github.com/jashkenas/coffeescript/tree/HEAD)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/1.9.1...HEAD)

**Implemented enhancements:**

- 1.9.1 [\#3862](https://github.com/jashkenas/coffeescript/issues/3862)

- Function overloading \(and enforcing number of parameters\) [\#2005](https://github.com/jashkenas/coffeescript/issues/2005)

- Can't compile a RegExp starting with a space \(e.g. / \*$/\) [\#1411](https://github.com/jashkenas/coffeescript/issues/1411)

**Fixed bugs:**

- `yield` keyword does not work in switch or for loop expressions, where `this` must be passed [\#3882](https://github.com/jashkenas/coffeescript/issues/3882)

- coffee --nodejs --harmony thorws customFds deprecation error [\#3868](https://github.com/jashkenas/coffeescript/issues/3868)

- Logo zip file not found [\#3627](https://github.com/jashkenas/coffeescript/issues/3627)

**Closed issues:**

- inline regex and split [\#3898](https://github.com/jashkenas/coffeescript/issues/3898)

- Error: The two following source files have the same output file [\#3863](https://github.com/jashkenas/coffeescript/issues/3863)

- Source Maps: Reference errors in 'name only expressions' are broken [\#3672](https://github.com/jashkenas/coffeescript/issues/3672)

**Merged pull requests:**

- Escape literal \] in regexp [\#3893](https://github.com/jashkenas/coffeescript/pull/3893) ([josh](https://github.com/josh))

- Added checking on process.stdout to be compatible with browserify [\#3892](https://github.com/jashkenas/coffeescript/pull/3892) ([matthieubulte](https://github.com/matthieubulte))

- Revert "Escape literal \[ in regexp" [\#3886](https://github.com/jashkenas/coffeescript/pull/3886) ([jashkenas](https://github.com/jashkenas))

- Escape literal \[ in regexp [\#3885](https://github.com/jashkenas/coffeescript/pull/3885) ([josh](https://github.com/josh))

- yield now behaves as expected around 'this' [\#3883](https://github.com/jashkenas/coffeescript/pull/3883) ([alubbe](https://github.com/alubbe))

- added descriptions to tests which only had Issue numbers [\#3877](https://github.com/jashkenas/coffeescript/pull/3877) ([gilesbowkett](https://github.com/gilesbowkett))

- Fix getting of character at index [\#3873](https://github.com/jashkenas/coffeescript/pull/3873) ([Taritsyn](https://github.com/Taritsyn))

- Update README.md and remove README [\#3872](https://github.com/jashkenas/coffeescript/pull/3872) ([banyan](https://github.com/banyan))

- Replace references to jQuery's 'bind' with 'on' [\#3871](https://github.com/jashkenas/coffeescript/pull/3871) ([jcrben](https://github.com/jcrben))

- add -r/--require command line option [\#3867](https://github.com/jashkenas/coffeescript/pull/3867) ([sgentle](https://github.com/sgentle))

- Optionally to read data-src out from <script\> [\#3706](https://github.com/jashkenas/coffeescript/pull/3706) ([imcotton](https://github.com/imcotton))

- Use stdio option instead of customFds [\#3661](https://github.com/jashkenas/coffeescript/pull/3661) ([dtaniwaki](https://github.com/dtaniwaki))

- Avoid error when --nodejs --use\_strict [\#3875](https://github.com/jashkenas/coffeescript/pull/3875) ([yuukinajima](https://github.com/yuukinajima))

## [1.9.1](https://github.com/jashkenas/coffeescript/tree/1.9.1) (2015-02-18)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/1.9.0...1.9.1)

**Implemented enhancements:**

- Allow dynamic keys for object \(hash\) definition [\#3597](https://github.com/jashkenas/coffeescript/issues/3597)

- Clarify error messages for attempted key interpolation [\#1131](https://github.com/jashkenas/coffeescript/issues/1131)

**Fixed bugs:**

- "yield return" from a conditional does not return if followed by a statement [\#3837](https://github.com/jashkenas/coffeescript/issues/3837)

- CS1.9 returns wrong position for string properties in object literals [\#3822](https://github.com/jashkenas/coffeescript/issues/3822)

- Compiler can write several times the same file without warning and producing garabage [\#3753](https://github.com/jashkenas/coffeescript/issues/3753)

- Interpolated dynamic keys are allowed if the interpolation string is empty [\#3039](https://github.com/jashkenas/coffeescript/issues/3039)

- calling `super` in methods defined on namespaced classes [\#1392](https://github.com/jashkenas/coffeescript/issues/1392)

**Closed issues:**

- repl test breaks on 0.12 [\#3855](https://github.com/jashkenas/coffeescript/issues/3855)

- Weird array being inserted into a generated brace \({\) token [\#3846](https://github.com/jashkenas/coffeescript/issues/3846)

- Extra 'end of interpolation' tag [\#3831](https://github.com/jashkenas/coffeescript/issues/3831)

- `do variable = \(name = 2\) -\>` doesn't test parameter for null when calling [\#3820](https://github.com/jashkenas/coffeescript/issues/3820)

- In 1.9.0, Coffeescript breaks Angular dependency injection [\#3816](https://github.com/jashkenas/coffeescript/issues/3816)

- Invalid generated string literals [\#3795](https://github.com/jashkenas/coffeescript/issues/3795)

- Add character range to tokens [\#2172](https://github.com/jashkenas/coffeescript/issues/2172)

**Merged pull requests:**

- Fix single-line heredocs starting with "undefined" [\#3861](https://github.com/jashkenas/coffeescript/pull/3861) ([lydell](https://github.com/lydell))

- fixed overly fragile repl test to work with 0.12 [\#3858](https://github.com/jashkenas/coffeescript/pull/3858) ([alubbe](https://github.com/alubbe))

- fixed yield return producing incorrect output when used outside of the last line [\#3854](https://github.com/jashkenas/coffeescript/pull/3854) ([alubbe](https://github.com/alubbe))

- fixed being unable to use 'yield throw' [\#3853](https://github.com/jashkenas/coffeescript/pull/3853) ([alubbe](https://github.com/alubbe))

- added a lot of ES6 generator tests [\#3852](https://github.com/jashkenas/coffeescript/pull/3852) ([alubbe](https://github.com/alubbe))

- Fix \#3846: Fix odd start token of implicit objects [\#3850](https://github.com/jashkenas/coffeescript/pull/3850) ([lydell](https://github.com/lydell))

- Fix error message for invalid escape at end of regex [\#3849](https://github.com/jashkenas/coffeescript/pull/3849) ([lydell](https://github.com/lydell))

- Fixed copyright range to be updated to 2015 [\#3842](https://github.com/jashkenas/coffeescript/pull/3842) ([arianf](https://github.com/arianf))

- Replace `last array` helper with `\[..., last\] = array` [\#3841](https://github.com/jashkenas/coffeescript/pull/3841) ([lydell](https://github.com/lydell))

- Fix \#3597: Allow interpolations in object keys [\#3840](https://github.com/jashkenas/coffeescript/pull/3840) ([lydell](https://github.com/lydell))

- Improve lexer error messages [\#3834](https://github.com/jashkenas/coffeescript/pull/3834) ([lydell](https://github.com/lydell))

- Fix \#3795: Never generate invalid strings and regexes [\#3833](https://github.com/jashkenas/coffeescript/pull/3833) ([lydell](https://github.com/lydell))

- Fix incorrect token representation [\#3830](https://github.com/jashkenas/coffeescript/pull/3830) ([swang](https://github.com/swang))

- Improve error messages for unexpected regexes [\#3827](https://github.com/jashkenas/coffeescript/pull/3827) ([lydell](https://github.com/lydell))

- Fix \#3822: Include delimiters in string/regex locations [\#3826](https://github.com/jashkenas/coffeescript/pull/3826) ([lydell](https://github.com/lydell))

- Name generated variables without leading underscore [\#3821](https://github.com/jashkenas/coffeescript/pull/3821) ([lydell](https://github.com/lydell))

- Allow multiline comment at end of an object definition \[Fixes \#3761\] [\#3802](https://github.com/jashkenas/coffeescript/pull/3802) ([mapmeld](https://github.com/mapmeld))

- Fix \#3778: Make for loops more consistent [\#3786](https://github.com/jashkenas/coffeescript/pull/3786) ([lydell](https://github.com/lydell))

- Allow super in methods with dynamic names [\#3785](https://github.com/jashkenas/coffeescript/pull/3785) ([lydell](https://github.com/lydell))

- Prevent writing the same file several times \(fixes \#3753\) [\#3758](https://github.com/jashkenas/coffeescript/pull/3758) ([DiThi](https://github.com/DiThi))

- Rebuild browser file [\#3851](https://github.com/jashkenas/coffeescript/pull/3851) ([mbrio](https://github.com/mbrio))

- Extended hook after class body execution [\#3289](https://github.com/jashkenas/coffeescript/pull/3289) ([tgriesser](https://github.com/tgriesser))

## [1.9.0](https://github.com/jashkenas/coffeescript/tree/1.9.0) (2015-01-29)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/1.8.0...1.9.0)

**Implemented enhancements:**

- Regular expressions can't start with whitespace [\#3756](https://github.com/jashkenas/coffeescript/issues/3756)

- Interpolations at beginning of strings compile to an empty string concatenation [\#3529](https://github.com/jashkenas/coffeescript/issues/3529)

- regexp with equal /=/ [\#3182](https://github.com/jashkenas/coffeescript/issues/3182)

- Pipeline support [\#1339](https://github.com/jashkenas/coffeescript/issues/1339)

**Fixed bugs:**

- Sometimes possible to alter how many times a for loop is run, sometimes not [\#3778](https://github.com/jashkenas/coffeescript/issues/3778)

- Coffeescript test suite errors after parser build? [\#3750](https://github.com/jashkenas/coffeescript/issues/3750)

- yield should have a lower priority in the order of operations [\#3674](https://github.com/jashkenas/coffeescript/issues/3674)

- “Unexpected by/when” in `for \[a..b\]` shorthand [\#3671](https://github.com/jashkenas/coffeescript/issues/3671)

- yield keyword does not work in for loop expression [\#3665](https://github.com/jashkenas/coffeescript/issues/3665)

- Multiline RegExp with string interpolation do not get marked as such. [\#3621](https://github.com/jashkenas/coffeescript/issues/3621)

- Problems using `lib/coffee-script/parser.js` [\#3608](https://github.com/jashkenas/coffeescript/issues/3608)

- Variable definitions missing when \(unnamed\) splat arguments are used [\#3502](https://github.com/jashkenas/coffeescript/issues/3502)

- Inserted paren reported as unexpected token instead of EOF [\#3455](https://github.com/jashkenas/coffeescript/issues/3455)

- Fails to parse regex starting with space [\#3410](https://github.com/jashkenas/coffeescript/issues/3410)

- Bad error messages for unterminated strings [\#3394](https://github.com/jashkenas/coffeescript/issues/3394)

- Location data is wrong in interpolations with leading whitespace [\#3348](https://github.com/jashkenas/coffeescript/issues/3348)

- Bad lexing of triple quoted regex and strings [\#3301](https://github.com/jashkenas/coffeescript/issues/3301)

- `For Range ForExtra` [\#3241](https://github.com/jashkenas/coffeescript/issues/3241)

- String interpolation in array [\#3194](https://github.com/jashkenas/coffeescript/issues/3194)

- Bug: u00A0 Character not treated as whitespace. [\#2516](https://github.com/jashkenas/coffeescript/issues/2516)

- `"""` in heredoc interpolations break heredocs [\#2388](https://github.com/jashkenas/coffeescript/issues/2388)

- Interpolation bug [\#2321](https://github.com/jashkenas/coffeescript/issues/2321)

- possible to shadow \_arg in parameter list [\#1574](https://github.com/jashkenas/coffeescript/issues/1574)

- Temporary variables should not be accessible from user code [\#1500](https://github.com/jashkenas/coffeescript/issues/1500)

- Can't create a regex that starts with = [\#1399](https://github.com/jashkenas/coffeescript/issues/1399)

- Single token misinterpolation [\#1316](https://github.com/jashkenas/coffeescript/issues/1316)

**Closed issues:**

- Broken REPL \(throws for any source that needs `scope.freeVariable`\) [\#3804](https://github.com/jashkenas/coffeescript/issues/3804)

- invalid message when compiling broken coffee file [\#3799](https://github.com/jashkenas/coffeescript/issues/3799)

- do keyword followed by assignment of function definition loses its default value [\#3776](https://github.com/jashkenas/coffeescript/issues/3776)

- Multiline comment  in object parse problem [\#3761](https://github.com/jashkenas/coffeescript/issues/3761)

- Unary `+` and `-` do not generate `\_ref`s, which coerces the operand more than once \(inconsistent\) [\#3598](https://github.com/jashkenas/coffeescript/issues/3598)

- compilation error with attribute access [\#3560](https://github.com/jashkenas/coffeescript/issues/3560)

- Disallow bare references to ivar params [\#3318](https://github.com/jashkenas/coffeescript/issues/3318)

**Merged pull requests:**

- Update index.html.js [\#3812](https://github.com/jashkenas/coffeescript/pull/3812) ([xfq](https://github.com/xfq))

- Fix broken CoffeeScript APIs [\#3808](https://github.com/jashkenas/coffeescript/pull/3808) ([lydell](https://github.com/lydell))

- Fix \#3804: Provide list of referenced vars to REPL [\#3807](https://github.com/jashkenas/coffeescript/pull/3807) ([lydell](https://github.com/lydell))

- Decouple "mkdirp". [\#3800](https://github.com/jashkenas/coffeescript/pull/3800) ([ysmood](https://github.com/ysmood))

- Fixed broken link [\#3798](https://github.com/jashkenas/coffeescript/pull/3798) ([ogennadi](https://github.com/ogennadi))

- Make CoffeeScript work with jison 0.4.14+ [\#3794](https://github.com/jashkenas/coffeescript/pull/3794) ([lydell](https://github.com/lydell))

- Fix \#3194: Make strings always uncallable [\#3792](https://github.com/jashkenas/coffeescript/pull/3792) ([lydell](https://github.com/lydell))

- Fix \#3502: Define param variables when expansion [\#3791](https://github.com/jashkenas/coffeescript/pull/3791) ([lydell](https://github.com/lydell))

- Get rid of `Scope.root` hack [\#3790](https://github.com/jashkenas/coffeescript/pull/3790) ([lydell](https://github.com/lydell))

- Better error message for unexpected CALL\_END [\#3788](https://github.com/jashkenas/coffeescript/pull/3788) ([lydell](https://github.com/lydell))

- Fix \#1316: Interpolate interpolations safely [\#3787](https://github.com/jashkenas/coffeescript/pull/3787) ([lydell](https://github.com/lydell))

- Unique generated vars [\#3784](https://github.com/jashkenas/coffeescript/pull/3784) ([lydell](https://github.com/lydell))

- Fix \#3671: Allow step in optimized range comprehensions [\#3783](https://github.com/jashkenas/coffeescript/pull/3783) ([lydell](https://github.com/lydell))

- Fix \#3410, \#3182: Allow regex to start with space or = [\#3782](https://github.com/jashkenas/coffeescript/pull/3782) ([lydell](https://github.com/lydell))

- Fix \#3598: Make unary + and - generate \_refs [\#3777](https://github.com/jashkenas/coffeescript/pull/3777) ([lydell](https://github.com/lydell))

- Fix \#2516, \#3560: Unicode space handling [\#3774](https://github.com/jashkenas/coffeescript/pull/3774) ([lydell](https://github.com/lydell))

- Fix issue \#3498 [\#3771](https://github.com/jashkenas/coffeescript/pull/3771) ([mbrio](https://github.com/mbrio))

- Refactor interpolation \(and string and regex\) handling in lexer [\#3770](https://github.com/jashkenas/coffeescript/pull/3770) ([lydell](https://github.com/lydell))

- Include logo .svg files [\#3748](https://github.com/jashkenas/coffeescript/pull/3748) ([sscotth](https://github.com/sscotth))

- fixed yield keyword not working in switch & for loop expressions [\#3734](https://github.com/jashkenas/coffeescript/pull/3734) ([alubbe](https://github.com/alubbe))

- Add existential bookmark to documentation/index.html.js [\#3715](https://github.com/jashkenas/coffeescript/pull/3715) ([tyre](https://github.com/tyre))

- Add anchor to existential operator header [\#3713](https://github.com/jashkenas/coffeescript/pull/3713) ([tyre](https://github.com/tyre))

- Add bower.json configuration [\#3703](https://github.com/jashkenas/coffeescript/pull/3703) ([bigtunacan](https://github.com/bigtunacan))

- implemented proper precedence for 'yield' [\#3677](https://github.com/jashkenas/coffeescript/pull/3677) ([alubbe](https://github.com/alubbe))

- Invalid block comments compilation [\#3638](https://github.com/jashkenas/coffeescript/pull/3638) ([lbeschastny](https://github.com/lbeschastny))

- Refresh site Examples section [\#3618](https://github.com/jashkenas/coffeescript/pull/3618) ([josh](https://github.com/josh))

- Quick spelling fixes [\#3616](https://github.com/jashkenas/coffeescript/pull/3616) ([epmatsw](https://github.com/epmatsw))

- Retina favicon.ico [\#3521](https://github.com/jashkenas/coffeescript/pull/3521) ([gscottolson](https://github.com/gscottolson))

- Fixes broken REPL \(fixes \#3804\) [\#3805](https://github.com/jashkenas/coffeescript/pull/3805) ([Artazor](https://github.com/Artazor))

- Update dependency on mkdirp [\#3552](https://github.com/jashkenas/coffeescript/pull/3552) ([flowlo](https://github.com/flowlo))

- Added yield and yield from [\#3316](https://github.com/jashkenas/coffeescript/pull/3316) ([xixixao](https://github.com/xixixao))

## [1.8.0](https://github.com/jashkenas/coffeescript/tree/1.8.0) (2014-08-26)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/1.7.1...1.8.0)

**Implemented enhancements:**

- Source maps: --join support? [\#2779](https://github.com/jashkenas/coffeescript/issues/2779)

**Fixed bugs:**

- coffeescript.org: 404 for link to best examples :\) [\#3550](https://github.com/jashkenas/coffeescript/issues/3550)

- The web site has an outdated link for "CoffeeScript Ristretto." [\#3489](https://github.com/jashkenas/coffeescript/issues/3489)

- repl.js broken in HEAD? [\#3395](https://github.com/jashkenas/coffeescript/issues/3395)

- repl: cannot `throw new SyntaxError` [\#3388](https://github.com/jashkenas/coffeescript/issues/3388)

- Unbalanced single-quoted strings break the Lexer [\#3379](https://github.com/jashkenas/coffeescript/issues/3379)

- Anotated source in `gh-pages` branch not compiled [\#3374](https://github.com/jashkenas/coffeescript/issues/3374)

- %% coercing order [\#3363](https://github.com/jashkenas/coffeescript/issues/3363)

- %% coerces the right operand thrice [\#3361](https://github.com/jashkenas/coffeescript/issues/3361)

- coffee sometimes fails silently when using -p -j -c together [\#2063](https://github.com/jashkenas/coffeescript/issues/2063)

**Closed issues:**

- Get rid of --join [\#3472](https://github.com/jashkenas/coffeescript/issues/3472)

- --join can change the semantics of joined source files [\#3307](https://github.com/jashkenas/coffeescript/issues/3307)

**Merged pull requests:**

- Release 1.8.0 [\#3611](https://github.com/jashkenas/coffeescript/pull/3611) ([lydell](https://github.com/lydell))

- Exit with an error code 1 if could not write a compiled JavaScript file ... [\#3592](https://github.com/jashkenas/coffeescript/pull/3592) ([mmotorny](https://github.com/mmotorny))

- Use '.js.map' as file extension for created map files [\#3561](https://github.com/jashkenas/coffeescript/pull/3561) ([yjo](https://github.com/yjo))

- `bin/cake` will be in `coffeescript` [\#3545](https://github.com/jashkenas/coffeescript/pull/3545) ([jordanbtucker](https://github.com/jordanbtucker))

- Fixed an error formatting issue [\#3543](https://github.com/jashkenas/coffeescript/pull/3543) ([ysmood](https://github.com/ysmood))

- Fix wrong location issue in heregex interpolation [\#3539](https://github.com/jashkenas/coffeescript/pull/3539) ([minodisk](https://github.com/minodisk))

- Fix wrong location issue in "string" interpolation [\#3533](https://github.com/jashkenas/coffeescript/pull/3533) ([minodisk](https://github.com/minodisk))

- Fix location data bug for string interpolations [\#3524](https://github.com/jashkenas/coffeescript/pull/3524) ([minodisk](https://github.com/minodisk))

- Remove sudo from install command in introduction [\#3509](https://github.com/jashkenas/coffeescript/pull/3509) ([aviflax](https://github.com/aviflax))

- remove docco as dependency \(still a devDependency\) [\#3508](https://github.com/jashkenas/coffeescript/pull/3508) ([bwin](https://github.com/bwin))

- Handle dotless commands in the REPL. [\#3503](https://github.com/jashkenas/coffeescript/pull/3503) ([datenreisender](https://github.com/datenreisender))

- Fix “list of open-source CoffeeScript on GitHub” [\#3494](https://github.com/jashkenas/coffeescript/pull/3494) ([ELLIOTTCABLE](https://github.com/ELLIOTTCABLE))

- Do not rely on properties order in scope tests [\#3492](https://github.com/jashkenas/coffeescript/pull/3492) ([forty](https://github.com/forty))

- Add tests to check that the FOR variable is defined after the loop [\#3491](https://github.com/jashkenas/coffeescript/pull/3491) ([forty](https://github.com/forty))

- command: deprecate --join [\#3477](https://github.com/jashkenas/coffeescript/pull/3477) ([davidchambers](https://github.com/davidchambers))

- Fix help for .load [\#3460](https://github.com/jashkenas/coffeescript/pull/3460) ([datenreisender](https://github.com/datenreisender))

- Fix repl for Node 0.11.12. [\#3450](https://github.com/jashkenas/coffeescript/pull/3450) ([ehuss](https://github.com/ehuss))

- Export the CoffeeScript REPL. [\#3448](https://github.com/jashkenas/coffeescript/pull/3448) ([leedm777](https://github.com/leedm777))

- Display compile errors - rebase from @jeremybanks [\#3425](https://github.com/jashkenas/coffeescript/pull/3425) ([charlierudolph](https://github.com/charlierudolph))

- Fix errors on index [\#3424](https://github.com/jashkenas/coffeescript/pull/3424) ([charlierudolph](https://github.com/charlierudolph))

- fix spell mistake on index.html.js [\#3418](https://github.com/jashkenas/coffeescript/pull/3418) ([fabricecolas](https://github.com/fabricecolas))

- Package with preferGlobal as appropriate for command-line application [\#3415](https://github.com/jashkenas/coffeescript/pull/3415) ([hickford](https://github.com/hickford))

- fix a spell mistake in cakefile [\#3401](https://github.com/jashkenas/coffeescript/pull/3401) ([sailxjx](https://github.com/sailxjx))

- Convert README to Markdown [\#3393](https://github.com/jashkenas/coffeescript/pull/3393) ([christianbundy](https://github.com/christianbundy))

- Fixes issue \#3349, prints deprecation warning [\#3386](https://github.com/jashkenas/coffeescript/pull/3386) ([blmarket](https://github.com/blmarket))

- changelog: use time elements for release dates [\#3382](https://github.com/jashkenas/coffeescript/pull/3382) ([davidchambers](https://github.com/davidchambers))

- changelog: replace inline CSS [\#3381](https://github.com/jashkenas/coffeescript/pull/3381) ([davidchambers](https://github.com/davidchambers))

- Rudimentary fix for jashkenas/coffee-script\#3379. [\#3380](https://github.com/jashkenas/coffeescript/pull/3380) ([madprgmr](https://github.com/madprgmr))

- change log improvements [\#3376](https://github.com/jashkenas/coffeescript/pull/3376) ([davidchambers](https://github.com/davidchambers))

- Cakefile: register .coffee extension by default [\#3368](https://github.com/jashkenas/coffeescript/pull/3368) ([ricardobeat](https://github.com/ricardobeat))

- Fix \#3361, make %% coerce right operand only once [\#3362](https://github.com/jashkenas/coffeescript/pull/3362) ([epidemian](https://github.com/epidemian))

- Improve installation documentation [\#3360](https://github.com/jashkenas/coffeescript/pull/3360) ([lydell](https://github.com/lydell))

- Make patched stack traces’ prelude consistent with V8 [\#3359](https://github.com/jashkenas/coffeescript/pull/3359) ([lydell](https://github.com/lydell))

- Remove reference to never-defined .isUndefined property [\#3355](https://github.com/jashkenas/coffeescript/pull/3355) ([aroben](https://github.com/aroben))

- Fixed example29 [\#3578](https://github.com/jashkenas/coffeescript/pull/3578) ([bfab](https://github.com/bfab))

- Copy getters and setters from parent into child when extending [\#3537](https://github.com/jashkenas/coffeescript/pull/3537) ([joostverdoorn](https://github.com/joostverdoorn))

- Fix location data bug for string interpolations [\#3514](https://github.com/jashkenas/coffeescript/pull/3514) ([dabbler0](https://github.com/dabbler0))

- Update link to "CoffeeScript Ristretto" [\#3490](https://github.com/jashkenas/coffeescript/pull/3490) ([raganwald](https://github.com/raganwald))

- add crapscript [\#3473](https://github.com/jashkenas/coffeescript/pull/3473) ([ghost](https://github.com/ghost))

- Update critic example to treat strings as strings [\#3464](https://github.com/jashkenas/coffeescript/pull/3464) ([zzmp](https://github.com/zzmp))

- Fix error on index [\#3423](https://github.com/jashkenas/coffeescript/pull/3423) ([charlierudolph](https://github.com/charlierudolph))

- fix paragraph on index.html.js [\#3419](https://github.com/jashkenas/coffeescript/pull/3419) ([fabricecolas](https://github.com/fabricecolas))

- fix a spell mistake in index.html.js [\#3417](https://github.com/jashkenas/coffeescript/pull/3417) ([fabricecolas](https://github.com/fabricecolas))

- Improve error messages for unterminated strings [\#3392](https://github.com/jashkenas/coffeescript/pull/3392) ([lydell](https://github.com/lydell))

- CodeMirror submodule, styling, and implementation [\#3353](https://github.com/jashkenas/coffeescript/pull/3353) ([ZombieHippie](https://github.com/ZombieHippie))

- Add --no-beep to command, to suppress --watch bell [\#3346](https://github.com/jashkenas/coffeescript/pull/3346) ([mietek](https://github.com/mietek))

- Add tab key usage to try-it editor [\#3342](https://github.com/jashkenas/coffeescript/pull/3342) ([ZombieHippie](https://github.com/ZombieHippie))

- Restrict duplicate keys [\#2352](https://github.com/jashkenas/coffeescript/pull/2352) ([michaelficarra](https://github.com/michaelficarra))

## [1.7.1](https://github.com/jashkenas/coffeescript/tree/1.7.1) (2014-01-30)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/1.7.0...1.7.1)

**Fixed bugs:**

- Missing indentation warning [\#3338](https://github.com/jashkenas/coffeescript/issues/3338)

**Closed issues:**

- Release 1.7.0 [\#3332](https://github.com/jashkenas/coffeescript/issues/3332)

**Merged pull requests:**

- Fix a typo causing module.paths to be always set as the cwd. [\#3340](https://github.com/jashkenas/coffeescript/pull/3340) ([goffrie](https://github.com/goffrie))

- In docs, move commas out of code [\#3337](https://github.com/jashkenas/coffeescript/pull/3337) ([roryokane](https://github.com/roryokane))

- Fix markup in math operator documentation [\#3336](https://github.com/jashkenas/coffeescript/pull/3336) ([roryokane](https://github.com/roryokane))

- Just a small typo in 1.7.0 changelog [\#3334](https://github.com/jashkenas/coffeescript/pull/3334) ([dannguyen](https://github.com/dannguyen))

## [1.7.0](https://github.com/jashkenas/coffeescript/tree/1.7.0) (2014-01-28)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/1.6.3...1.7.0)

**Implemented enhancements:**

- Make it possible to assign multiple variables and object keys at once [\#3242](https://github.com/jashkenas/coffeescript/issues/3242)

- Function stubs? [\#3093](https://github.com/jashkenas/coffeescript/issues/3093)

- Add yield support [\#3073](https://github.com/jashkenas/coffeescript/issues/3073)

- Unnecessary \_ref when constructor is passed through a function [\#3008](https://github.com/jashkenas/coffeescript/issues/3008)

- Better compilation errors descriptions [\#2854](https://github.com/jashkenas/coffeescript/issues/2854)

- tighten scope of saved reference to external constructors [\#1969](https://github.com/jashkenas/coffeescript/issues/1969)

- Superfluous \_this when fat arrow is used in class body [\#1947](https://github.com/jashkenas/coffeescript/issues/1947)

- simplify negated existence compilation [\#1215](https://github.com/jashkenas/coffeescript/issues/1215)

- disallow `arguments`, `eval` in parameter lists [\#1007](https://github.com/jashkenas/coffeescript/issues/1007)

**Fixed bugs:**

- Wrong reported token [\#3325](https://github.com/jashkenas/coffeescript/issues/3325)

- CLI "coffee" doesn't work with datejs [\#3321](https://github.com/jashkenas/coffeescript/issues/3321)

- Correct line numbers in stack trace \(when requiring .coffee from a .js file\) [\#3282](https://github.com/jashkenas/coffeescript/issues/3282)

- Strict mode in extending classes [\#3273](https://github.com/jashkenas/coffeescript/issues/3273)

- Source maps don't get deleted when using --watch [\#3267](https://github.com/jashkenas/coffeescript/issues/3267)

- Interpolation Breaks Leading Whitespace in Heredocs [\#3264](https://github.com/jashkenas/coffeescript/issues/3264)

- Bug in destructuring assignment in function arguments [\#3259](https://github.com/jashkenas/coffeescript/issues/3259)

- Backslash at EOL in block strings [\#3249](https://github.com/jashkenas/coffeescript/issues/3249)

- --watch ignores some files [\#3235](https://github.com/jashkenas/coffeescript/issues/3235)

- super compiles differently depending on how class method is defined [\#3232](https://github.com/jashkenas/coffeescript/issues/3232)

- "for thing, i \(in|of\) things" doesn't compile inside an object definition [\#3216](https://github.com/jashkenas/coffeescript/issues/3216)

- return issue [\#3206](https://github.com/jashkenas/coffeescript/issues/3206)

- Different `Object` values in REPL [\#3197](https://github.com/jashkenas/coffeescript/issues/3197)

- TypeError when executing browser script [\#3186](https://github.com/jashkenas/coffeescript/issues/3186)

- if a then if b then c else d [\#3169](https://github.com/jashkenas/coffeescript/issues/3169)

- CANNOT READ PROPERTY 'LAST\_LINE' OF UNDEFINED [\#3160](https://github.com/jashkenas/coffeescript/issues/3160)

- Fat arrow leaks generated `\_this` reference to other closures [\#3143](https://github.com/jashkenas/coffeescript/issues/3143)

- TypeError: Cannot call method 'slice' of undefined [\#3140](https://github.com/jashkenas/coffeescript/issues/3140)

- SourceMaps outputed are an absolute mess [\#3092](https://github.com/jashkenas/coffeescript/issues/3092)

- "Uncaught ReferenceError: \_\_slice is not defined" using splats [\#3089](https://github.com/jashkenas/coffeescript/issues/3089)

- process.argv\[0\] is "node" in REPL [\#3072](https://github.com/jashkenas/coffeescript/issues/3072)

- Incorrectly indented return causes unexpected exception \(1.6.3\) [\#3063](https://github.com/jashkenas/coffeescript/issues/3063)

- Incorrect compilation of certain combinations of 'unless' and 'if' [\#3056](https://github.com/jashkenas/coffeescript/issues/3056)

- TypeError: Cannot call method 'error' of undefined in 1.6.3, works fine in 1.6.2 [\#3053](https://github.com/jashkenas/coffeescript/issues/3053)

- module.paths not set correctly when accepts input from stdin [\#3047](https://github.com/jashkenas/coffeescript/issues/3047)

- Unhelpful error messages when running under node.js [\#3030](https://github.com/jashkenas/coffeescript/issues/3030)

- When CoffeeScript is required, syntax errors are unhelpful [\#3023](https://github.com/jashkenas/coffeescript/issues/3023)

- Document null default arguments in function call creating test/set of null [\#3019](https://github.com/jashkenas/coffeescript/issues/3019)

- Incorrect Version Number [\#3006](https://github.com/jashkenas/coffeescript/issues/3006)

- if else one-liner [\#2994](https://github.com/jashkenas/coffeescript/issues/2994)

- Bundle with 1.6.2 script has incorrect version in package.json [\#2989](https://github.com/jashkenas/coffeescript/issues/2989)

- Initial indent at start of a file [\#2981](https://github.com/jashkenas/coffeescript/issues/2981)

- Error forking .coffee files when not installed globally [\#2957](https://github.com/jashkenas/coffeescript/issues/2957)

- Benchmark fails [\#2955](https://github.com/jashkenas/coffeescript/issues/2955)

- Compiler error when calling `super` from a method named with a reserved word [\#2949](https://github.com/jashkenas/coffeescript/issues/2949)

- --join option creates a ".js" file \(regression\) [\#2941](https://github.com/jashkenas/coffeescript/issues/2941)

- A typo in anotated documentation? Where can I find a list about CoffeeScript's API? [\#2926](https://github.com/jashkenas/coffeescript/issues/2926)

- --nodejs option didn't work with cluster module [\#2919](https://github.com/jashkenas/coffeescript/issues/2919)

- Incorrect global reference in repl [\#2883](https://github.com/jashkenas/coffeescript/issues/2883)

- coffeescript.org/extras/coffee-script.js throws a error when parsing multibyte strings [\#2880](https://github.com/jashkenas/coffeescript/issues/2880)

- 1.6.2 SourceMap documentation doesn't match implementation [\#2874](https://github.com/jashkenas/coffeescript/issues/2874)

- 1.6.2, node 0.8.14: `prettyErrorMessage` fails in require\(\)d script [\#2849](https://github.com/jashkenas/coffeescript/issues/2849)

- Compilation performance down 45% since 1.4.0 [\#2844](https://github.com/jashkenas/coffeescript/issues/2844)

- super fails inside of loop  [\#2367](https://github.com/jashkenas/coffeescript/issues/2367)

- Poor Compiler Information Bug [\#2285](https://github.com/jashkenas/coffeescript/issues/2285)

- Multiline Regex backslash behavior [\#2238](https://github.com/jashkenas/coffeescript/issues/2238)

- Chained use of the Existential operator caused function to be invoked multiple times. [\#2197](https://github.com/jashkenas/coffeescript/issues/2197)

- Bug in `unless` with conditional assignment [\#2181](https://github.com/jashkenas/coffeescript/issues/2181)

- `mkdir -p` doesn't work as expected on windows [\#2027](https://github.com/jashkenas/coffeescript/issues/2027)

- Inner class prevents subsequent property definitions [\#1981](https://github.com/jashkenas/coffeescript/issues/1981)

- Strange behavior with backticked javascript comments [\#1473](https://github.com/jashkenas/coffeescript/issues/1473)

- splicing statement [\#1376](https://github.com/jashkenas/coffeescript/issues/1376)

- trailing backslashes in strings [\#1273](https://github.com/jashkenas/coffeescript/issues/1273)

- f\(\) in \[\] [\#1099](https://github.com/jashkenas/coffeescript/issues/1099)

- Unexpected { in `a::b: -\>` [\#1096](https://github.com/jashkenas/coffeescript/issues/1096)

- disallow `arguments`, `eval` in parameter lists [\#1007](https://github.com/jashkenas/coffeescript/issues/1007)

**Closed issues:**

- one of cheat sheet's addresses is invalid [\#3245](https://github.com/jashkenas/coffeescript/issues/3245)

- Multiline strings like LiveScript [\#3229](https://github.com/jashkenas/coffeescript/issues/3229)

- Print variable name [\#3220](https://github.com/jashkenas/coffeescript/issues/3220)

- Chromium demanding change in source map URL declaration format [\#3135](https://github.com/jashkenas/coffeescript/issues/3135)

- Escape literal whitespace within Heregex \(not a dup!\) [\#3059](https://github.com/jashkenas/coffeescript/issues/3059)

- Use the new "\# sourceMappingURL=..." comment format when referencing source maps [\#3050](https://github.com/jashkenas/coffeescript/issues/3050)

- Add string support for `in` operator [\#3032](https://github.com/jashkenas/coffeescript/issues/3032)

- `coffee dir` executes every coffee file, vs `node dir` which executes `index.js` only. [\#2496](https://github.com/jashkenas/coffeescript/issues/2496)

- Require explicit require\(\) registration? \(And maybe local only?\) [\#2323](https://github.com/jashkenas/coffeescript/issues/2323)

- Allow newlines to be escaped in multi-line strings [\#1994](https://github.com/jashkenas/coffeescript/issues/1994)

- method k:v if condition [\#1871](https://github.com/jashkenas/coffeescript/issues/1871)

- Using === causes a compiler error [\#1775](https://github.com/jashkenas/coffeescript/issues/1775)

- Array slicing with negative end index is undocumented [\#1766](https://github.com/jashkenas/coffeescript/issues/1766)

- Sub-block terminator can cause parent block termination [\#1275](https://github.com/jashkenas/coffeescript/issues/1275)

- Multiline strings shouldn't get extra whitespaces [\#610](https://github.com/jashkenas/coffeescript/issues/610)

**Merged pull requests:**

- Implement \#3332 [\#3333](https://github.com/jashkenas/coffeescript/pull/3333) ([xixixao](https://github.com/xixixao))

- Fixes chaining after inline implicit objects [\#3331](https://github.com/jashkenas/coffeescript/pull/3331) ([xixixao](https://github.com/xixixao))

- Fixes \#3325: implicit indendation error messages [\#3329](https://github.com/jashkenas/coffeescript/pull/3329) ([xixixao](https://github.com/xixixao))

- Fixes \#3216 for declarations in object literals [\#3328](https://github.com/jashkenas/coffeescript/pull/3328) ([xixixao](https://github.com/xixixao))

- Fix expansion in destructuring inside comprehensions [\#3327](https://github.com/jashkenas/coffeescript/pull/3327) ([xixixao](https://github.com/xixixao))

- Prepare 1.7.0 release [\#3326](https://github.com/jashkenas/coffeescript/pull/3326) ([xixixao](https://github.com/xixixao))

- Fixes \#1871, close implicit objects in implicit returns [\#3324](https://github.com/jashkenas/coffeescript/pull/3324) ([xixixao](https://github.com/xixixao))

- Fix \#1099, remove in empty array optimization [\#3322](https://github.com/jashkenas/coffeescript/pull/3322) ([xixixao](https://github.com/xixixao))

- Fix \#1275 [\#3320](https://github.com/jashkenas/coffeescript/pull/3320) ([xixixao](https://github.com/xixixao))

- Fix 1096, 1131, 1828: Improve error messages for generated tokens [\#3319](https://github.com/jashkenas/coffeescript/pull/3319) ([xixixao](https://github.com/xixixao))

- Chaining semantics after arguments with outdent [\#3317](https://github.com/jashkenas/coffeescript/pull/3317) ([xixixao](https://github.com/xixixao))

- Fix `child\_process.fork` patch [\#3293](https://github.com/jashkenas/coffeescript/pull/3293) ([marchaefner](https://github.com/marchaefner))

- `coffee DIR` executes `DIR/index.coffee` [\#3292](https://github.com/jashkenas/coffeescript/pull/3292) ([marchaefner](https://github.com/marchaefner))

- Format utilities using single quoted literals [\#3285](https://github.com/jashkenas/coffeescript/pull/3285) ([xixixao](https://github.com/xixixao))

- Fix multiple postfix conditionals [\#3284](https://github.com/jashkenas/coffeescript/pull/3284) ([xixixao](https://github.com/xixixao))

- the page lists only top 100 contributors [\#3283](https://github.com/jashkenas/coffeescript/pull/3283) ([Fritz-Lium](https://github.com/Fritz-Lium))

- Examples: Back to non-naked constructor, @, preincrement, comprehension bracketing... [\#3280](https://github.com/jashkenas/coffeescript/pull/3280) ([xixixao](https://github.com/xixixao))

- fix require.extensions registration [\#3279](https://github.com/jashkenas/coffeescript/pull/3279) ([michaelficarra](https://github.com/michaelficarra))

- Add CoffeeScript in Action book link [\#3277](https://github.com/jashkenas/coffeescript/pull/3277) ([boundvariable](https://github.com/boundvariable))

- Fixup \#3263: Prevent loop collection in endAllImplicitCalls [\#3276](https://github.com/jashkenas/coffeescript/pull/3276) ([xixixao](https://github.com/xixixao))

- Fix --watch handling of deleted sources [\#3275](https://github.com/jashkenas/coffeescript/pull/3275) ([marchaefner](https://github.com/marchaefner))

- Implement \#1495,  Method call chaining [\#3263](https://github.com/jashkenas/coffeescript/pull/3263) ([xixixao](https://github.com/xixixao))

- Fix \#1766, Add negative slice end index into docs [\#3262](https://github.com/jashkenas/coffeescript/pull/3262) ([xixixao](https://github.com/xixixao))

- Fix \#1273, Handle backslashes at the end of heredocs [\#3261](https://github.com/jashkenas/coffeescript/pull/3261) ([xixixao](https://github.com/xixixao))

-  Implements \#3249, \#1994 Escape newlines in heredocs with backslashes [\#3256](https://github.com/jashkenas/coffeescript/pull/3256) ([xixixao](https://github.com/xixixao))

- CLI fixes and refactoring [\#3255](https://github.com/jashkenas/coffeescript/pull/3255) ([marchaefner](https://github.com/marchaefner))

- Fix multiple escaped backslashes in literal strings [\#3250](https://github.com/jashkenas/coffeescript/pull/3250) ([xixixao](https://github.com/xixixao))

- Implements \#3229 - Changed multiline string literals [\#3246](https://github.com/jashkenas/coffeescript/pull/3246) ([xixixao](https://github.com/xixixao))

- Fix super-related tagging of `Code` nodes [\#3237](https://github.com/jashkenas/coffeescript/pull/3237) ([marchaefner](https://github.com/marchaefner))

- Fixes \#3087 -- Use `fs.\*Sync` for CLI compilation [\#3234](https://github.com/jashkenas/coffeescript/pull/3234) ([marchaefner](https://github.com/marchaefner))

- Clean up `Method calls on splice endpoints` [\#3233](https://github.com/jashkenas/coffeescript/pull/3233) ([xixixao](https://github.com/xixixao))

- Avoid unnecessary wrapping of some bound functions [\#3228](https://github.com/jashkenas/coffeescript/pull/3228) ([marchaefner](https://github.com/marchaefner))

- Fix scope of external constructor reference / Refactor `Closure` [\#3227](https://github.com/jashkenas/coffeescript/pull/3227) ([marchaefner](https://github.com/marchaefner))

- Minor fixes for class compilation [\#3224](https://github.com/jashkenas/coffeescript/pull/3224) ([marchaefner](https://github.com/marchaefner))

- Escapable linebreaks in heregexes [\#3218](https://github.com/jashkenas/coffeescript/pull/3218) ([marchaefner](https://github.com/marchaefner))

- Escaped whitespace and slashes in Heregexes [\#3214](https://github.com/jashkenas/coffeescript/pull/3214) ([marchaefner](https://github.com/marchaefner))

- add: Stat polling support while `fs.watch` doesn't work. [\#3212](https://github.com/jashkenas/coffeescript/pull/3212) ([ysmood](https://github.com/ysmood))

- Fix compilation for conditional assignment [\#3211](https://github.com/jashkenas/coffeescript/pull/3211) ([marchaefner](https://github.com/marchaefner))

- Use cake to generate doc:site [\#3198](https://github.com/jashkenas/coffeescript/pull/3198) ([jiyinyiyong](https://github.com/jiyinyiyong))

- fixed ascii art inconsistencies in coffee's water vapor [\#3193](https://github.com/jashkenas/coffeescript/pull/3193) ([celwell](https://github.com/celwell))

- Fixes \#3186 [\#3189](https://github.com/jashkenas/coffeescript/pull/3189) ([mal](https://github.com/mal))

- Accept all format of numbers in ranges [\#3174](https://github.com/jashkenas/coffeescript/pull/3174) ([a3gis](https://github.com/a3gis))

- Fix constructor\_destructuring docs example to alert a defined value [\#3165](https://github.com/jashkenas/coffeescript/pull/3165) ([grschafer](https://github.com/grschafer))

- Fix some inconsistent indentation [\#3151](https://github.com/jashkenas/coffeescript/pull/3151) ([kchmck](https://github.com/kchmck))

- Fix: support for consumers of the REPL \*module\* being able to opt into using the global context ... [\#3150](https://github.com/jashkenas/coffeescript/pull/3150) ([mklement0](https://github.com/mklement0))

- Fix broken formatting in underscore.coffee docs [\#3146](https://github.com/jashkenas/coffeescript/pull/3146) ([phillipalexander](https://github.com/phillipalexander))

- Format block-comments better [\#3132](https://github.com/jashkenas/coffeescript/pull/3132) ([caitp](https://github.com/caitp))

- Make the REPL \*CLI\* use the global context to be consistent with the node REPL \*CLI\*. [\#3113](https://github.com/jashkenas/coffeescript/pull/3113) ([mklement0](https://github.com/mklement0))

- Issue \#3092: Fix column numbers in sourcemaps to not be essentially random. [\#3111](https://github.com/jashkenas/coffeescript/pull/3111) ([jwalton](https://github.com/jwalton))

- Fork with binary of coffee-script in use, rather than global [\#3107](https://github.com/jashkenas/coffeescript/pull/3107) ([mal](https://github.com/mal))

- recompile [\#3104](https://github.com/jashkenas/coffeescript/pull/3104) ([davidchambers](https://github.com/davidchambers))

- Fixed deep directory creation for command line utility [\#3101](https://github.com/jashkenas/coffeescript/pull/3101) ([FredyC](https://github.com/FredyC))

- Fix \#3023, Change how error messages are shown [\#3100](https://github.com/jashkenas/coffeescript/pull/3100) ([epidemian](https://github.com/epidemian))

- Disallow single-line `IF expr ELSE` without `THEN` [\#3096](https://github.com/jashkenas/coffeescript/pull/3096) ([marchaefner](https://github.com/marchaefner))

- Update compiled JS [\#3094](https://github.com/jashkenas/coffeescript/pull/3094) ([epidemian](https://github.com/epidemian))

- Updated the Source Maps syntax [\#3051](https://github.com/jashkenas/coffeescript/pull/3051) ([CaseyLeask](https://github.com/CaseyLeask))

- Avoid variable scope collision with extensions [\#3049](https://github.com/jashkenas/coffeescript/pull/3049) ([dpatti](https://github.com/dpatti))

- Fix path separator issues in tests. [\#3045](https://github.com/jashkenas/coffeescript/pull/3045) ([marchaefner](https://github.com/marchaefner))

- check existence of "path" for browser execution [\#3043](https://github.com/jashkenas/coffeescript/pull/3043) ([imcotton](https://github.com/imcotton))

- Avoid excessive AST traversal in `updateLocationDataIfMissing`. [\#3042](https://github.com/jashkenas/coffeescript/pull/3042) ([marchaefner](https://github.com/marchaefner))

- Better handling of initial indent at file start. [\#3034](https://github.com/jashkenas/coffeescript/pull/3034) ([marchaefner](https://github.com/marchaefner))

- Stack trace patch optimizations [\#3031](https://github.com/jashkenas/coffeescript/pull/3031) ([alexgorbatchev](https://github.com/alexgorbatchev))

- fix block comment format "\n" [\#3029](https://github.com/jashkenas/coffeescript/pull/3029) ([wangxian](https://github.com/wangxian))

- base path for compilation can be './' as well as '.' [\#3014](https://github.com/jashkenas/coffeescript/pull/3014) ([mset](https://github.com/mset))

- Script loading parallelized in browser [\#3012](https://github.com/jashkenas/coffeescript/pull/3012) ([imcotton](https://github.com/imcotton))

- Provide tests for keeping shebang lines in compiled CS files [\#3330](https://github.com/jashkenas/coffeescript/pull/3330) ([Alaneor](https://github.com/Alaneor))

- Offline one-click CS compiler [\#3308](https://github.com/jashkenas/coffeescript/pull/3308) ([jfcg](https://github.com/jfcg))

- Removes unnecessary closure [\#3271](https://github.com/jashkenas/coffeescript/pull/3271) ([ahmdrefat](https://github.com/ahmdrefat))

- bound functions do not perserve arities [\#3257](https://github.com/jashkenas/coffeescript/pull/3257) ([layerssss](https://github.com/layerssss))

- Add `--\>`  operator for non-returning functions [\#3209](https://github.com/jashkenas/coffeescript/pull/3209) ([L8D](https://github.com/L8D))

- Prevent coffee-script from overwriting itself with a different version [\#3208](https://github.com/jashkenas/coffeescript/pull/3208) ([demands](https://github.com/demands))

- Option to suppress or change "Generated by" header \(\#2353\) [\#3166](https://github.com/jashkenas/coffeescript/pull/3166) ([doublerebel](https://github.com/doublerebel))

- fix exit code when using --nodejs option [\#3147](https://github.com/jashkenas/coffeescript/pull/3147) ([a3gis](https://github.com/a3gis))

- trdggg [\#3144](https://github.com/jashkenas/coffeescript/pull/3144) ([owenkop](https://github.com/owenkop))

- Fix formatting in underscore.coffee documentation \(generated html\) [\#3130](https://github.com/jashkenas/coffeescript/pull/3130) ([phillipalexander](https://github.com/phillipalexander))

- Call compile\(\) as the callback for mkdir [\#3103](https://github.com/jashkenas/coffeescript/pull/3103) ([FredyC](https://github.com/FredyC))

- ditto [\#3097](https://github.com/jashkenas/coffeescript/pull/3097) ([vendethiel](https://github.com/vendethiel))

- Fixed inaccuracy in the docs \#3082 [\#3083](https://github.com/jashkenas/coffeescript/pull/3083) ([olleicua](https://github.com/olleicua))

- fix bug in command.coffee file. [\#3071](https://github.com/jashkenas/coffeescript/pull/3071) ([liouys](https://github.com/liouys))

- NavMenu max-height & overflow:scroll for smaller screens. [\#3067](https://github.com/jashkenas/coffeescript/pull/3067) ([quangv](https://github.com/quangv))

- Stop modifying require.extensions in the top level. [\#3054](https://github.com/jashkenas/coffeescript/pull/3054) ([BYVoid](https://github.com/BYVoid))

- optional determine literate coffee by its suffix [\#3044](https://github.com/jashkenas/coffeescript/pull/3044) ([imcotton](https://github.com/imcotton))

- Patch stack trace optimizations [\#3026](https://github.com/jashkenas/coffeescript/pull/3026) ([alexgorbatchev](https://github.com/alexgorbatchev))

- Added combined comparison operator. [\#3024](https://github.com/jashkenas/coffeescript/pull/3024) ([vtsvang](https://github.com/vtsvang))

- Fixes \#2981 [\#2985](https://github.com/jashkenas/coffeescript/pull/2985) ([xixixao](https://github.com/xixixao))

- Parameter check needed [\#2187](https://github.com/jashkenas/coffeescript/pull/2187) ([evgenyneu](https://github.com/evgenyneu))

- Object extension literal [\#2177](https://github.com/jashkenas/coffeescript/pull/2177) ([itrelease](https://github.com/itrelease))

- Added detection for Windows builds and modified execution of mkdir comma... [\#2091](https://github.com/jashkenas/coffeescript/pull/2091) ([spencerelliott](https://github.com/spencerelliott))

- Issue \#1768 - allow spacing for \[ when following '::' operator. [\#1824](https://github.com/jashkenas/coffeescript/pull/1824) ([kellypleahy](https://github.com/kellypleahy))

- Fix sudo bin/cake install [\#1345](https://github.com/jashkenas/coffeescript/pull/1345) ([willmoffat](https://github.com/willmoffat))

## [1.6.3](https://github.com/jashkenas/coffeescript/tree/1.6.3) (2013-06-02)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/1.6.2...1.6.3)

**Implemented enhancements:**

- source maps with coffee-script binary [\#2787](https://github.com/jashkenas/coffeescript/issues/2787)

- Source maps: <script type="text/coffeescript"\> support? [\#2780](https://github.com/jashkenas/coffeescript/issues/2780)

- mention js2coffee in the documentation [\#2478](https://github.com/jashkenas/coffeescript/issues/2478)

- New Stab at Source Maps [\#2256](https://github.com/jashkenas/coffeescript/issues/2256)

- Mod/intdiv Mathematical Operators to Work Around JavaScript Oddities [\#1971](https://github.com/jashkenas/coffeescript/issues/1971)

- Extended/Included/Initialized Callback? [\#1883](https://github.com/jashkenas/coffeescript/issues/1883)

- `super` in class declaration as alias for parent class [\#1790](https://github.com/jashkenas/coffeescript/issues/1790)

- compiler error for variable use before declaration [\#1555](https://github.com/jashkenas/coffeescript/issues/1555)

- Idea: Mark generated JS files as generated [\#1454](https://github.com/jashkenas/coffeescript/issues/1454)

- Conditional assignment generates unneeded code [\#1437](https://github.com/jashkenas/coffeescript/issues/1437)

- `for x in \[range\] by \[constant\]` performance [\#1356](https://github.com/jashkenas/coffeescript/issues/1356)

**Fixed bugs:**

- `own` contextual keyword mistakenly allowed in for-in loops [\#3001](https://github.com/jashkenas/coffeescript/issues/3001)

- Full-line comments in script literals \(regression\) [\#2996](https://github.com/jashkenas/coffeescript/issues/2996)

- --nouse-idle-notification and --expose-gc and cluster [\#2971](https://github.com/jashkenas/coffeescript/issues/2971)

- Assignment from an array splice literal breaks when calling methods on its limits [\#2953](https://github.com/jashkenas/coffeescript/issues/2953)

- Cannot omit parens when passing a regexp literal to a method accessed via square bracket notation [\#2944](https://github.com/jashkenas/coffeescript/issues/2944)

- Requiring literate coffee in Node.js [\#2928](https://github.com/jashkenas/coffeescript/issues/2928)

- cannot place comment line before ajaxPost [\#2916](https://github.com/jashkenas/coffeescript/issues/2916)

- Missing '\n' between expressions. [\#2908](https://github.com/jashkenas/coffeescript/issues/2908)

- Cluster test fails on Windows [\#2891](https://github.com/jashkenas/coffeescript/issues/2891)

- helpers.baseFileName should use a platform independent path separator [\#2866](https://github.com/jashkenas/coffeescript/issues/2866)

- file handling by compiler in Windows after 1.6.2 [\#2857](https://github.com/jashkenas/coffeescript/issues/2857)

- index.coffee.md no longer recognized as default main in node packages [\#2855](https://github.com/jashkenas/coffeescript/issues/2855)

- INVALID\_CHARACTER\_ERR: DOM Exception 5 [\#2853](https://github.com/jashkenas/coffeescript/issues/2853)

- Crash with --compile --map [\#2846](https://github.com/jashkenas/coffeescript/issues/2846)

- Literate mode: incorrect column in locationData / source maps. [\#2835](https://github.com/jashkenas/coffeescript/issues/2835)

- "coffee -c src/ -o out/" incorrectly maps input-output folders [\#2778](https://github.com/jashkenas/coffeescript/issues/2778)

- Bug: Unexpected 'CALL\_END' in 'Post If Condition' lambda function. [\#2555](https://github.com/jashkenas/coffeescript/issues/2555)

- Destructuring assignment confused by two @variables in function call [\#2332](https://github.com/jashkenas/coffeescript/issues/2332)

- Method call in class definition doesn't allow paren omission [\#2330](https://github.com/jashkenas/coffeescript/issues/2330)

- Object destructuring parameters' attribute names counted as parameter names [\#2305](https://github.com/jashkenas/coffeescript/issues/2305)

- Top-level block in REPL [\#2241](https://github.com/jashkenas/coffeescript/issues/2241)

- string interpolated parameter generates different function call [\#2145](https://github.com/jashkenas/coffeescript/issues/2145)

- a: b d:e doesn't work [\#2086](https://github.com/jashkenas/coffeescript/issues/2086)

- unexpected results with ||= and ?= for multi-line object literals [\#2066](https://github.com/jashkenas/coffeescript/issues/2066)

- In an object literal: syntax error when passing an anonymous function as a parameter [\#2064](https://github.com/jashkenas/coffeescript/issues/2064)

- if a b=c [\#1998](https://github.com/jashkenas/coffeescript/issues/1998)

- Sub-Object function arguments' Parse Error [\#1773](https://github.com/jashkenas/coffeescript/issues/1773)

- Can’t pass a function call as argument after a braceless object argument [\#1615](https://github.com/jashkenas/coffeescript/issues/1615)

- bug: `class extends` as function arg with @assignment as first line [\#1557](https://github.com/jashkenas/coffeescript/issues/1557)

- Executable class bodies, objects, and optional parentheses. Bug?  [\#1341](https://github.com/jashkenas/coffeescript/issues/1341)

- Calling a function while defining a prototype value in a class definition fails [\#1304](https://github.com/jashkenas/coffeescript/issues/1304)

- object literal [\#1111](https://github.com/jashkenas/coffeescript/issues/1111)

- Array literals are implicitly callable [\#1069](https://github.com/jashkenas/coffeescript/issues/1069)

- -\> try finally [\#1057](https://github.com/jashkenas/coffeescript/issues/1057)

**Closed issues:**

- Catch Should Not Require Param [\#2900](https://github.com/jashkenas/coffeescript/issues/2900)

- Fix parsing of indented markdown features by requiring line-break delimiter [\#2821](https://github.com/jashkenas/coffeescript/issues/2821)

- F A Q [\#2316](https://github.com/jashkenas/coffeescript/issues/2316)

- implied tokens create incomprehensible error messages [\#2160](https://github.com/jashkenas/coffeescript/issues/2160)

- Adding Whitespace to Compiled JS [\#1713](https://github.com/jashkenas/coffeescript/issues/1713)

- Expand Resources section of site [\#1418](https://github.com/jashkenas/coffeescript/issues/1418)

- `that` variable inside functions defined using =\> [\#1230](https://github.com/jashkenas/coffeescript/issues/1230)

**Merged pull requests:**

- Disallowed `for own in` [\#3002](https://github.com/jashkenas/coffeescript/pull/3002) ([vendethiel](https://github.com/vendethiel))

- Patch module.prototype.load to enable multiple extensions like .coffee.md [\#3000](https://github.com/jashkenas/coffeescript/pull/3000) ([sgentle](https://github.com/sgentle))

- Fixes tabbed code test in literate [\#2984](https://github.com/jashkenas/coffeescript/pull/2984) ([xixixao](https://github.com/xixixao))

- Fix 'propeties' typo in docs [\#2978](https://github.com/jashkenas/coffeescript/pull/2978) ([pushrax](https://github.com/pushrax))

- Show correct line and column for errors occurring inside require\(\)d coffee script files [\#2968](https://github.com/jashkenas/coffeescript/pull/2968) ([chajath](https://github.com/chajath))

- Style cleanup [\#2965](https://github.com/jashkenas/coffeescript/pull/2965) ([vendethiel](https://github.com/vendethiel))

- Lint flag removal [\#2963](https://github.com/jashkenas/coffeescript/pull/2963) ([vendethiel](https://github.com/vendethiel))

- Fix \#1069. Non-callable literals shouldn't compile [\#2954](https://github.com/jashkenas/coffeescript/pull/2954) ([xixixao](https://github.com/xixixao))

- Fix \#1437. Unneeded ref in existential assignment. [\#2951](https://github.com/jashkenas/coffeescript/pull/2951) ([xixixao](https://github.com/xixixao))

- Fix \#2944 [\#2946](https://github.com/jashkenas/coffeescript/pull/2946) ([vendethiel](https://github.com/vendethiel))

- fix warning in REPL tests about memory leak. [\#2943](https://github.com/jashkenas/coffeescript/pull/2943) ([bobbydavid](https://github.com/bobbydavid))

- Fixes \#2908, add "\n" between pure literal header and function body. [\#2940](https://github.com/jashkenas/coffeescript/pull/2940) ([jiangmiao](https://github.com/jiangmiao))

- Fix implicit calls with preceding herecomment [\#2933](https://github.com/jashkenas/coffeescript/pull/2933) ([marchaefner](https://github.com/marchaefner))

- Fixes \#1057: Allow catch/finally in single line functions. [\#2930](https://github.com/jashkenas/coffeescript/pull/2930) ([marchaefner](https://github.com/marchaefner))

- Keep a single-line herecomment as a single-line js comment. [\#2929](https://github.com/jashkenas/coffeescript/pull/2929) ([lucasb-eyer](https://github.com/lucasb-eyer))

- Fix error reporting for invalid object key. [\#2925](https://github.com/jashkenas/coffeescript/pull/2925) ([marchaefner](https://github.com/marchaefner))

- Parameter-less catch clause. [\#2924](https://github.com/jashkenas/coffeescript/pull/2924) ([marchaefner](https://github.com/marchaefner))

- repl history implementation improvements [\#2914](https://github.com/jashkenas/coffeescript/pull/2914) ([michaelficarra](https://github.com/michaelficarra))

- Literate flag [\#2894](https://github.com/jashkenas/coffeescript/pull/2894) ([billymoon](https://github.com/billymoon))

- fix \#2846 [\#2890](https://github.com/jashkenas/coffeescript/pull/2890) ([vendethiel](https://github.com/vendethiel))

- Add history to the coffee interactive interpreter that persists between ... [\#2886](https://github.com/jashkenas/coffeescript/pull/2886) ([danielgtaylor](https://github.com/danielgtaylor))

- Fix Windows path separator issue in `baseFileName`. [\#2869](https://github.com/jashkenas/coffeescript/pull/2869) ([marchaefner](https://github.com/marchaefner))

- encode unicode src, test added [\#2867](https://github.com/jashkenas/coffeescript/pull/2867) ([hden](https://github.com/hden))

- quick-fix [\#2865](https://github.com/jashkenas/coffeescript/pull/2865) ([hden](https://github.com/hden))

- More explicit window context. [\#2851](https://github.com/jashkenas/coffeescript/pull/2851) ([toots](https://github.com/toots))

- Browser source map [\#2847](https://github.com/jashkenas/coffeescript/pull/2847) ([hden](https://github.com/hden))

- fix path handling on Windows [\#2840](https://github.com/jashkenas/coffeescript/pull/2840) ([MattKunze](https://github.com/MattKunze))

- Improve literal mode. [\#2838](https://github.com/jashkenas/coffeescript/pull/2838) ([marchaefner](https://github.com/marchaefner))

- Lineno [\#2827](https://github.com/jashkenas/coffeescript/pull/2827) ([hden](https://github.com/hden))

- Bump engines.node version on package.json to 0.8 [\#2826](https://github.com/jashkenas/coffeescript/pull/2826) ([epidemian](https://github.com/epidemian))

- Quick fix for node v0.10 path [\#2819](https://github.com/jashkenas/coffeescript/pull/2819) ([hden](https://github.com/hden))

- Keep REPL running on runtime errors [\#2817](https://github.com/jashkenas/coffeescript/pull/2817) ([epidemian](https://github.com/epidemian))

- rake task creates/installs coffeescript.syntax [\#2085](https://github.com/jashkenas/coffeescript/pull/2085) ([stepheneb](https://github.com/stepheneb))

- Fix REPL when env.HOME isn't available [\#2945](https://github.com/jashkenas/coffeescript/pull/2945) ([vendethiel](https://github.com/vendethiel))

- sumbols-like strings [\#2935](https://github.com/jashkenas/coffeescript/pull/2935) ([printercu](https://github.com/printercu))

- 'TypeError: object is not a function' when compiling with sourceMap: true using extras/coffee-script.js [\#2934](https://github.com/jashkenas/coffeescript/pull/2934) ([maxatwork](https://github.com/maxatwork))

- copy properties, not just fields [\#2902](https://github.com/jashkenas/coffeescript/pull/2902) ([toshok](https://github.com/toshok))

- quick-fix for 2891 [\#2892](https://github.com/jashkenas/coffeescript/pull/2892) ([hden](https://github.com/hden))

- Expose CoffeeScript repl to allow building custom interactive shells [\#2885](https://github.com/jashkenas/coffeescript/pull/2885) ([danielgtaylor](https://github.com/danielgtaylor))

- Add version information and a line about help in the coffeescript interactive shell [\#2884](https://github.com/jashkenas/coffeescript/pull/2884) ([danielgtaylor](https://github.com/danielgtaylor))

- Fix \#2861 inline sourcemaps line number mismatching [\#2863](https://github.com/jashkenas/coffeescript/pull/2863) ([hden](https://github.com/hden))

- Fix: Inline sourcemaps line number mismatching [\#2862](https://github.com/jashkenas/coffeescript/pull/2862) ([hden](https://github.com/hden))

- a bit more OS agnostic [\#2839](https://github.com/jashkenas/coffeescript/pull/2839) ([fredericosilva](https://github.com/fredericosilva))

- Provide hooks for setting static and prototype properties. [\#2329](https://github.com/jashkenas/coffeescript/pull/2329) ([lancejpollard](https://github.com/lancejpollard))

- Line mappings [\#2050](https://github.com/jashkenas/coffeescript/pull/2050) ([thejh](https://github.com/thejh))

- Add a power operator [\#2026](https://github.com/jashkenas/coffeescript/pull/2026) ([charliesome](https://github.com/charliesome))

- \#1896 a: func b, {c: d} fix [\#2017](https://github.com/jashkenas/coffeescript/pull/2017) ([jaekwon](https://github.com/jaekwon))

- fat\_arrow documentation example clarification [\#1730](https://github.com/jashkenas/coffeescript/pull/1730) ([lorensr](https://github.com/lorensr))

- Added --require option to the Cakefile. [\#1480](https://github.com/jashkenas/coffeescript/pull/1480) ([taku0](https://github.com/taku0))

- ES5 bind [\#1408](https://github.com/jashkenas/coffeescript/pull/1408) ([michaelficarra](https://github.com/michaelficarra))

## [1.6.2](https://github.com/jashkenas/coffeescript/tree/1.6.2) (2013-03-13)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/1.6.1...1.6.2)

**Implemented enhancements:**

- Implicit switch if function has single parameter and consists of when clauses [\#2490](https://github.com/jashkenas/coffeescript/issues/2490)

**Fixed bugs:**

- How do you use the require option? [\#2808](https://github.com/jashkenas/coffeescript/issues/2808)

- Compiler crashes when it encounters a super call from a cleverly disguised non-method. [\#2798](https://github.com/jashkenas/coffeescript/issues/2798)

- Fat Arrow and Argument Destructuring [\#2790](https://github.com/jashkenas/coffeescript/issues/2790)

- Fat-arrow functions with non-alphanumeric characters cause error during construction in 1.6 [\#2782](https://github.com/jashkenas/coffeescript/issues/2782)

- Incorrect file path in sourcemap file in 1.6.1 [\#2774](https://github.com/jashkenas/coffeescript/issues/2774)

- --join not working with mixed literate/regular input [\#2768](https://github.com/jashkenas/coffeescript/issues/2768)

- catch does not create its own lexical environment [\#2422](https://github.com/jashkenas/coffeescript/issues/2422)

- break and continue causes looping expression to return empty array [\#1222](https://github.com/jashkenas/coffeescript/issues/1222)

- bind specialty? [\#1077](https://github.com/jashkenas/coffeescript/issues/1077)

- interpolated things are implicitly callable [\#1066](https://github.com/jashkenas/coffeescript/issues/1066)

- @k: v [\#1055](https://github.com/jashkenas/coffeescript/issues/1055)

- Inconsistent line numbers within interpolations [\#1041](https://github.com/jashkenas/coffeescript/issues/1041)

- Braceless object after `if` [\#981](https://github.com/jashkenas/coffeescript/issues/981)

**Closed issues:**

- REPL for coffee 1.5.0 and 1.6.1 errors out on node 0.6 [\#2813](https://github.com/jashkenas/coffeescript/issues/2813)

- Annotated Source [\#2783](https://github.com/jashkenas/coffeescript/issues/2783)

- 1.6.0 Broke overwriting a bound method [\#2773](https://github.com/jashkenas/coffeescript/issues/2773)

- Variable scope in functions defined in the REPL [\#1829](https://github.com/jashkenas/coffeescript/issues/1829)

**Merged pull requests:**

- added warning that repl needs node.js \>= 0.8 [\#2824](https://github.com/jashkenas/coffeescript/pull/2824) ([iamwilhelm](https://github.com/iamwilhelm))

- Source maps in node [\#2820](https://github.com/jashkenas/coffeescript/pull/2820) ([hden](https://github.com/hden))

- Fixes \#1829. Preserve variable scope in the REPL [\#2814](https://github.com/jashkenas/coffeescript/pull/2814) ([epidemian](https://github.com/epidemian))

- Fix typo in documentation [\#2810](https://github.com/jashkenas/coffeescript/pull/2810) ([SonicHedgehog](https://github.com/SonicHedgehog))

- Rework source map files and paths [\#2803](https://github.com/jashkenas/coffeescript/pull/2803) ([jwalton](https://github.com/jwalton))

- Fix: compiling `coffee.coffee` produces `.js` file. [\#2795](https://github.com/jashkenas/coffeescript/pull/2795) ([fahad19](https://github.com/fahad19))

- Fix for \#2774: Incorrect file path in sourcemap file in 1.6.1 [\#2793](https://github.com/jashkenas/coffeescript/pull/2793) ([jwalton](https://github.com/jwalton))

- Fix \#2768: support --join'ing mixed literate and non-literate CoffeeScript source files [\#2776](https://github.com/jashkenas/coffeescript/pull/2776) ([mintplant](https://github.com/mintplant))

- Minor improvements for locationData of tokens and some clean up. [\#2772](https://github.com/jashkenas/coffeescript/pull/2772) ([marchaefner](https://github.com/marchaefner))

- Move sourceMappingURL to bottom of generated JavaScript file. [\#2770](https://github.com/jashkenas/coffeescript/pull/2770) ([jwalton](https://github.com/jwalton))

- Documentation for switch statements with no control expression [\#2417](https://github.com/jashkenas/coffeescript/pull/2417) ([gabehollombe](https://github.com/gabehollombe))

- fix path handling on Windows [\#2802](https://github.com/jashkenas/coffeescript/pull/2802) ([MattKunze](https://github.com/MattKunze))

- Fixes \#2782: non-alphanumeric bound member names [\#2785](https://github.com/jashkenas/coffeescript/pull/2785) ([davidmfoley](https://github.com/davidmfoley))

- Jam support [\#2395](https://github.com/jashkenas/coffeescript/pull/2395) ([caolan](https://github.com/caolan))

- new switch -g --shebang to prepend shebang node to compiled Javascript [\#2391](https://github.com/jashkenas/coffeescript/pull/2391) ([hickford](https://github.com/hickford))

- Added source excerpt in compiler error messages. \#1351 [\#2369](https://github.com/jashkenas/coffeescript/pull/2369) ([STRd6](https://github.com/STRd6))

## [1.6.1](https://github.com/jashkenas/coffeescript/tree/1.6.1) (2013-03-04)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/1.6.0...1.6.1)

**Fixed bugs:**

- 1.6 breaks compile option \(OSX, node v0.8.20\) [\#2766](https://github.com/jashkenas/coffeescript/issues/2766)

- Incorrect Source Map Lines [\#2765](https://github.com/jashkenas/coffeescript/issues/2765)

**Merged pull requests:**

- Fixes \#2766 [\#2767](https://github.com/jashkenas/coffeescript/pull/2767) ([azylman](https://github.com/azylman))

- Use "map" instead of "maps" for option name [\#2764](https://github.com/jashkenas/coffeescript/pull/2764) ([matthewwithanm](https://github.com/matthewwithanm))

## [1.6.0](https://github.com/jashkenas/coffeescript/tree/1.6.0) (2013-03-04)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/1.5.0...1.6.0)

**Implemented enhancements:**

- Expand Literate CoffeeScript to include .litcoffee.md and/or .coffee.md suffixes [\#2736](https://github.com/jashkenas/coffeescript/issues/2736)

- Add class?::method syntax [\#2185](https://github.com/jashkenas/coffeescript/issues/2185)

**Fixed bugs:**

- Unexpected OUTDENT when trailing comma used in object inside class [\#2757](https://github.com/jashkenas/coffeescript/issues/2757)

- parser issue with passing classes to functions [\#2756](https://github.com/jashkenas/coffeescript/issues/2756)

- 5dea70b82e6dcc68b0f1c40642ba9a1bb1396a1b [\#2750](https://github.com/jashkenas/coffeescript/issues/2750)

- 6b79af2b7c25ebcb209be14687915fe53f0fc329 [\#2749](https://github.com/jashkenas/coffeescript/issues/2749)

- "WHEN" keyword not parsed correctly when used as a key [\#2735](https://github.com/jashkenas/coffeescript/issues/2735)

- coffee --interactive exits on runtime error [\#2716](https://github.com/jashkenas/coffeescript/issues/2716)

- Function argument without parenthesis should get passed to nearest antecedent function call [\#2557](https://github.com/jashkenas/coffeescript/issues/2557)

- Brace-less Object Literal as a Second Operand on a New Line [\#2549](https://github.com/jashkenas/coffeescript/issues/2549)

- Comma after function param in object literal doesn't work? [\#2509](https://github.com/jashkenas/coffeescript/issues/2509)

- Prototype and the existential operator [\#2508](https://github.com/jashkenas/coffeescript/issues/2508)

- Parethesizing objects in a class object call\(?\) has weird behavior [\#2502](https://github.com/jashkenas/coffeescript/issues/2502)

- Failure to compile file names with backslashes [\#2466](https://github.com/jashkenas/coffeescript/issues/2466)

- Indentation on the very first line [\#1027](https://github.com/jashkenas/coffeescript/issues/1027)

**Closed issues:**

- \#2599 is too strict \("cant return from a constructor"\) [\#2728](https://github.com/jashkenas/coffeescript/issues/2728)

- Define a UTI type for CoffeeScript and Literate CoffeeScript files. [\#2727](https://github.com/jashkenas/coffeescript/issues/2727)

- Having 'super' call 'this' in object members [\#2717](https://github.com/jashkenas/coffeescript/issues/2717)

- Document special behavior for using fat arrows to define class methods [\#2492](https://github.com/jashkenas/coffeescript/issues/2492)

**Merged pull requests:**

- Fix Source Map Generation for 1.6.0 [\#2763](https://github.com/jashkenas/coffeescript/pull/2763) ([matthewwithanm](https://github.com/matthewwithanm))

- Fix line number mismatch when first line is indented. [\#2752](https://github.com/jashkenas/coffeescript/pull/2752) ([marchaefner](https://github.com/marchaefner))

- Source maps for CoffeeScript [\#2751](https://github.com/jashkenas/coffeescript/pull/2751) ([jwalton](https://github.com/jwalton))

- Disallow implicit calls in cases like: [\#2746](https://github.com/jashkenas/coffeescript/pull/2746) ([troels](https://github.com/troels))

- Revert \#2599 [\#2743](https://github.com/jashkenas/coffeescript/pull/2743) ([epidemian](https://github.com/epidemian))

- Fix implicit calls with try/catch/finally as arguments [\#2741](https://github.com/jashkenas/coffeescript/pull/2741) ([troels](https://github.com/troels))

- Hoist build function to top level of Cakefile [\#2740](https://github.com/jashkenas/coffeescript/pull/2740) ([mintplant](https://github.com/mintplant))

- Fix \#2737: set process.execPath for cluster module [\#2739](https://github.com/jashkenas/coffeescript/pull/2739) ([mintplant](https://github.com/mintplant))

- Modify extension handling to allow for .coffee.md [\#2738](https://github.com/jashkenas/coffeescript/pull/2738) ([mintplant](https://github.com/mintplant))

- Fix REPL crashing on execution error [\#2725](https://github.com/jashkenas/coffeescript/pull/2725) ([mintplant](https://github.com/mintplant))

- Minor embellishments [\#2719](https://github.com/jashkenas/coffeescript/pull/2719) ([epidemian](https://github.com/epidemian))

- Add support for text/literate-coffeescript in the browser [\#2718](https://github.com/jashkenas/coffeescript/pull/2718) ([sbp](https://github.com/sbp))

- Implicit object/implicit call interaction handling [\#2712](https://github.com/jashkenas/coffeescript/pull/2712) ([troels](https://github.com/troels))

- Cake 'invoke' callback [\#2733](https://github.com/jashkenas/coffeescript/pull/2733) ([mahnunchik](https://github.com/mahnunchik))

- Fix for \#2715 [\#2730](https://github.com/jashkenas/coffeescript/pull/2730) ([mintplant](https://github.com/mintplant))

- Add postfix return statements [\#2729](https://github.com/jashkenas/coffeescript/pull/2729) ([mintplant](https://github.com/mintplant))

- Add "procedures": functions that are guaranteed to not return a value [\#2726](https://github.com/jashkenas/coffeescript/pull/2726) ([mintplant](https://github.com/mintplant))

- Fix compiler error when compiling 'super\(\)' [\#2721](https://github.com/jashkenas/coffeescript/pull/2721) ([epidemian](https://github.com/epidemian))

- Add a failing test case for multiline nested method calls \#2715 [\#2720](https://github.com/jashkenas/coffeescript/pull/2720) ([byroot](https://github.com/byroot))

- baseDir truncated when running coffee compiler with options 'coffee -co ../js ./ [\#2546](https://github.com/jashkenas/coffeescript/pull/2546) ([shavrin-ivan](https://github.com/shavrin-ivan))

- Line-number Mappings \(\#558\) [\#2483](https://github.com/jashkenas/coffeescript/pull/2483) ([kevinjdolan](https://github.com/kevinjdolan))

- Avoid breaking on ENOTDIR errors [\#2467](https://github.com/jashkenas/coffeescript/pull/2467) ([attilaolah](https://github.com/attilaolah))

## [1.5.0](https://github.com/jashkenas/coffeescript/tree/1.5.0) (2013-02-25)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/1.4.0...1.5.0)

**Implemented enhancements:**

- Add the "do \(x = y\) -\>" feature to the docs [\#2639](https://github.com/jashkenas/coffeescript/issues/2639)

- REPL refactor proposal [\#2626](https://github.com/jashkenas/coffeescript/issues/2626)

- Inconsistent conditionals: `if !a?`, `unless a?`, `when a?`, `when !a?` [\#2567](https://github.com/jashkenas/coffeescript/issues/2567)

- REPL: implement node's `.save` and `.load` [\#2355](https://github.com/jashkenas/coffeescript/issues/2355)

**Fixed bugs:**

- Splat\#compile calls non-existant @compileParam [\#2702](https://github.com/jashkenas/coffeescript/issues/2702)

- litcoffee broke `cake bench` [\#2690](https://github.com/jashkenas/coffeescript/issues/2690)

- Example compiler hook code does not seem to work  [\#2681](https://github.com/jashkenas/coffeescript/issues/2681)

- Files with UTF8 BOM not compiling correctly. [\#2650](https://github.com/jashkenas/coffeescript/issues/2650)

- Unclosed block comment should be syntax error [\#2645](https://github.com/jashkenas/coffeescript/issues/2645)

- Accessing arguments inside a class definition is broken [\#2630](https://github.com/jashkenas/coffeescript/issues/2630)

- broken destrcutive assignments when retreiving arguments [\#2621](https://github.com/jashkenas/coffeescript/issues/2621)

- if × if-then-else × implicit object literal = Parse error [\#2617](https://github.com/jashkenas/coffeescript/issues/2617)

- Complex destructing assignments make wrong code [\#2613](https://github.com/jashkenas/coffeescript/issues/2613)

- Destructure catch parameter [\#2580](https://github.com/jashkenas/coffeescript/issues/2580)

- Looping backwards over an existing array <change\> [\#2525](https://github.com/jashkenas/coffeescript/issues/2525)

- Cannot fork\(\) javascript files when run with 'coffee' command [\#2523](https://github.com/jashkenas/coffeescript/issues/2523)

- `cake build:full` uses old compiler for tests instead of the just built one [\#1580](https://github.com/jashkenas/coffeescript/issues/1580)

- indented property access bug [\#1435](https://github.com/jashkenas/coffeescript/issues/1435)

**Closed issues:**

- Add CoffeeScript Risttretto to the free online books section [\#2700](https://github.com/jashkenas/coffeescript/issues/2700)

- Enable repl colors for windows [\#2531](https://github.com/jashkenas/coffeescript/issues/2531)

**Merged pull requests:**

- Fix \#1435 by amending away sign reversal. [\#2711](https://github.com/jashkenas/coffeescript/pull/2711) ([troels](https://github.com/troels))

- Build:full sometimes uses old code when running tests. [\#2710](https://github.com/jashkenas/coffeescript/pull/2710) ([troels](https://github.com/troels))

- Minor embellishments [\#2709](https://github.com/jashkenas/coffeescript/pull/2709) ([epidemian](https://github.com/epidemian))

- Add source-location-awareness to coffee-script compiler. [\#2696](https://github.com/jashkenas/coffeescript/pull/2696) ([jwalton](https://github.com/jwalton))

- add license information to the gemspec [\#2685](https://github.com/jashkenas/coffeescript/pull/2685) ([jordimassaguerpla](https://github.com/jordimassaguerpla))

- REPL rewrite [\#2682](https://github.com/jashkenas/coffeescript/pull/2682) ([michaelficarra](https://github.com/michaelficarra))

- CoffeeScript REPL based on Node REPL [\#2669](https://github.com/jashkenas/coffeescript/pull/2669) ([asalant](https://github.com/asalant))

- gh-2631 Update to uglifyjs's new API [\#2632](https://github.com/jashkenas/coffeescript/pull/2632) ([caseywebdev](https://github.com/caseywebdev))

- Parse compound assignment operator followed by a terminator. Closes \#2532. [\#2627](https://github.com/jashkenas/coffeescript/pull/2627) ([int3](https://github.com/int3))

- tests for the repl [\#2600](https://github.com/jashkenas/coffeescript/pull/2600) ([lihanli](https://github.com/lihanli))

- Issue \#2359 fix: avoid "other typed" constructors [\#2599](https://github.com/jashkenas/coffeescript/pull/2599) ([epidemian](https://github.com/epidemian))

- Adding Testing with CoffeeScript to books list [\#2480](https://github.com/jashkenas/coffeescript/pull/2480) ([jamierumbelow](https://github.com/jamierumbelow))

- fixed riak urls [\#2701](https://github.com/jashkenas/coffeescript/pull/2701) ([janpieper](https://github.com/janpieper))

- Support for named functions [\#2666](https://github.com/jashkenas/coffeescript/pull/2666) ([milgner](https://github.com/milgner))

- add `transient` as a JavaScript keyword [\#2661](https://github.com/jashkenas/coffeescript/pull/2661) ([jochenberger](https://github.com/jochenberger))

- Reduce brackets of If statement for js size optimization [\#2646](https://github.com/jashkenas/coffeescript/pull/2646) ([c9s](https://github.com/c9s))

- Add noglobals compile option to generate self-contained functions [\#2634](https://github.com/jashkenas/coffeescript/pull/2634) ([jcorbin](https://github.com/jcorbin))

- Depend on uglify-js 1, 2 has new API [\#2631](https://github.com/jashkenas/coffeescript/pull/2631) ([d-snp](https://github.com/d-snp))

- Partial function application [\#2597](https://github.com/jashkenas/coffeescript/pull/2597) ([gampleman](https://github.com/gampleman))

- tests for the repl [\#2574](https://github.com/jashkenas/coffeescript/pull/2574) ([lihanli](https://github.com/lihanli))

## [1.4.0](https://github.com/jashkenas/coffeescript/tree/1.4.0) (2012-10-23)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/1.3.3...1.4.0)

**Implemented enhancements:**

- Arrow keys in REPL on Mac 10.7.4 \(coffeescript 1.3.3\) print '^\[\[A' etc. [\#2420](https://github.com/jashkenas/coffeescript/issues/2420)

- Mixed Tabs and Spaces -- Issue an Error or At Least a Warning [\#2384](https://github.com/jashkenas/coffeescript/issues/2384)

- "do" for loop [\#2382](https://github.com/jashkenas/coffeescript/issues/2382)

- Allow line breaks in function parameter lists  [\#1135](https://github.com/jashkenas/coffeescript/issues/1135)

**Fixed bugs:**

- baseDir truncated when runnin coffee compiler with options 'coffee -co ../js ./ [\#2545](https://github.com/jashkenas/coffeescript/issues/2545)

- browser.coffee: don't pass a string argument to the XMLHttpRequest constructor [\#2534](https://github.com/jashkenas/coffeescript/issues/2534)

- Line numbers in error messages do not match file when using raw javascript [\#2521](https://github.com/jashkenas/coffeescript/issues/2521)

- unexpected precedence [\#2506](https://github.com/jashkenas/coffeescript/issues/2506)

- x\[.."1"\] [\#2349](https://github.com/jashkenas/coffeescript/issues/2349)

- duplicate property still possible [\#2333](https://github.com/jashkenas/coffeescript/issues/2333)

- Inconsistently shadow variables in closure [\#1552](https://github.com/jashkenas/coffeescript/issues/1552)

- Coffee doesn't compile files in UTF-8 with signature [\#798](https://github.com/jashkenas/coffeescript/issues/798)

- `new` operator misbehavior [\#619](https://github.com/jashkenas/coffeescript/issues/619)

**Closed issues:**

- Instructions for installing latest master version with npm [\#2577](https://github.com/jashkenas/coffeescript/issues/2577)

- remove registerExtension support \(gone since node 0.2\) [\#2441](https://github.com/jashkenas/coffeescript/issues/2441)

- Let `function` keyword be part of Coffee [\#2402](https://github.com/jashkenas/coffeescript/issues/2402)

- Make "// Generated by CoffeeScript" optional [\#2353](https://github.com/jashkenas/coffeescript/issues/2353)

- Unexpected less than \(<\) operator precedence [\#1958](https://github.com/jashkenas/coffeescript/issues/1958)

- Multiline strings and multiline interpolations [\#608](https://github.com/jashkenas/coffeescript/issues/608)

**Merged pull requests:**

- Simplify Call.prototype.compileSplat based on how Traceur does it [\#2587](https://github.com/jashkenas/coffeescript/pull/2587) ([sstur](https://github.com/sstur))

- Fix \#2534: Don't pass a string argument to the XMLHttpRequest constructor [\#2535](https://github.com/jashkenas/coffeescript/pull/2535) ([philikon](https://github.com/philikon))

- Fixes \#2441: Remove \(deprecated\) registerExtension support. [\#2484](https://github.com/jashkenas/coffeescript/pull/2484) ([paulyoung](https://github.com/paulyoung))

- Add test script to package.json. [\#2431](https://github.com/jashkenas/coffeescript/pull/2431) ([domenic](https://github.com/domenic))

- Strip UTF-8 BOM when require'ing .coffee modules. [\#2430](https://github.com/jashkenas/coffeescript/pull/2430) ([domenic](https://github.com/domenic))

- Migrate from path.exists to fs.exists [\#2411](https://github.com/jashkenas/coffeescript/pull/2411) ([mintplant](https://github.com/mintplant))

- Add example of destructuring assignment in constructors for easy options initialization [\#2378](https://github.com/jashkenas/coffeescript/pull/2378) ([gabehollombe](https://github.com/gabehollombe))

- delete unused sentence [\#2371](https://github.com/jashkenas/coffeescript/pull/2371) ([takkaw](https://github.com/takkaw))

- fix repl completion and navigation [\#2347](https://github.com/jashkenas/coffeescript/pull/2347) ([heyLu](https://github.com/heyLu))

- fixes \#2333: fix prohibition of duplicate object properties [\#2334](https://github.com/jashkenas/coffeescript/pull/2334) ([michaelficarra](https://github.com/michaelficarra))

- Fixes font antialiasing [\#2527](https://github.com/jashkenas/coffeescript/pull/2527) ([nebjak](https://github.com/nebjak))

- Add 'export' keyword [\#2513](https://github.com/jashkenas/coffeescript/pull/2513) ([vanviegen](https://github.com/vanviegen))

- Fixing similar issues as \#1944 [\#2486](https://github.com/jashkenas/coffeescript/pull/2486) ([uberscientist](https://github.com/uberscientist))

- Added \_this and \_super to reserved words list [\#2461](https://github.com/jashkenas/coffeescript/pull/2461) ([almost](https://github.com/almost))

- Changed calls from path.exists to fs.exists [\#2421](https://github.com/jashkenas/coffeescript/pull/2421) ([TigerWolf](https://github.com/TigerWolf))

- Add support for UTF8 byte order marker [\#2389](https://github.com/jashkenas/coffeescript/pull/2389) ([milgner](https://github.com/milgner))

- updates to quiet "path.exists & path.existsSync is deprecated" warnings [\#2373](https://github.com/jashkenas/coffeescript/pull/2373) ([csmosx](https://github.com/csmosx))

- Added column numbers to tokens [\#2346](https://github.com/jashkenas/coffeescript/pull/2346) ([pyalot](https://github.com/pyalot))

- Beautiful literate programming. [\#1789](https://github.com/jashkenas/coffeescript/pull/1789) ([revence27](https://github.com/revence27))

## [1.3.3](https://github.com/jashkenas/coffeescript/tree/1.3.3) (2012-05-15)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/1.3.2...1.3.3)

**Implemented enhancements:**

- Release 1.3.2 [\#2282](https://github.com/jashkenas/coffeescript/issues/2282)

**Fixed bugs:**

- Bound instance method `super` calls run in the context of the class [\#2331](https://github.com/jashkenas/coffeescript/issues/2331)

- REPL incompatible with spawned process STDIN [\#2328](https://github.com/jashkenas/coffeescript/issues/2328)

## [1.3.2](https://github.com/jashkenas/coffeescript/tree/1.3.2) (2012-05-14)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/1.3.1...1.3.2)

**Implemented enhancements:**

- branding resources [\#2275](https://github.com/jashkenas/coffeescript/issues/2275)

- @-var as loop iterator [\#2274](https://github.com/jashkenas/coffeescript/issues/2274)

**Fixed bugs:**

- `for` variable shadowing with destructuring [\#2273](https://github.com/jashkenas/coffeescript/issues/2273)

- --join fails silently with 1.3.1. Works on 1.2.0 [\#2263](https://github.com/jashkenas/coffeescript/issues/2263)

- Splats on properties are missing a var declaration [\#2255](https://github.com/jashkenas/coffeescript/issues/2255)

- Can't pipe or redirect to coffee? [\#2251](https://github.com/jashkenas/coffeescript/issues/2251)

- Classes broken in latest update with strict mode enabled [\#2250](https://github.com/jashkenas/coffeescript/issues/2250)

- Single for loop in object literal fails to compile [\#2227](https://github.com/jashkenas/coffeescript/issues/2227)

- Coffee-script build fails on Windows [\#2217](https://github.com/jashkenas/coffeescript/issues/2217)

- Splat Value "xx" has no method 'isArray' [\#2211](https://github.com/jashkenas/coffeescript/issues/2211)

- Incorrect comprehension compilation in 1.2 [\#2207](https://github.com/jashkenas/coffeescript/issues/2207)

- `super` and wrapped statement [\#1183](https://github.com/jashkenas/coffeescript/issues/1183)

**Closed issues:**

- Generated \_\_extends fails lint with "Missing '\(\)' invoking a constructor." [\#2287](https://github.com/jashkenas/coffeescript/issues/2287)

- REPL missing completions? [\#2280](https://github.com/jashkenas/coffeescript/issues/2280)

- Line breaks in parameter lists [\#2258](https://github.com/jashkenas/coffeescript/issues/2258)

- rename cake shell [\#2254](https://github.com/jashkenas/coffeescript/issues/2254)

**Merged pull requests:**

- Fix typo in test name [\#2320](https://github.com/jashkenas/coffeescript/pull/2320) ([colinscape](https://github.com/colinscape))

- Wraps up \#2211 -- addresses invocations within destructured params [\#2299](https://github.com/jashkenas/coffeescript/pull/2299) ([geraldalewis](https://github.com/geraldalewis))

- Reapply the removed patch from bugfix\_1183 in PR 2252.  Include a test case to show it's required. [\#2281](https://github.com/jashkenas/coffeescript/pull/2281) ([maxtaco](https://github.com/maxtaco))

- Destructured assignment params incorrectly identified as duplicates. [\#2277](https://github.com/jashkenas/coffeescript/pull/2277) ([geraldalewis](https://github.com/geraldalewis))

- See issue \#2620 [\#2261](https://github.com/jashkenas/coffeescript/pull/2261) ([josher19](https://github.com/josher19))

- Bugfix 1183 [\#2252](https://github.com/jashkenas/coffeescript/pull/2252) ([maxtaco](https://github.com/maxtaco))

- build on Windows - fix spawn command by calling node explicitly [\#2219](https://github.com/jashkenas/coffeescript/pull/2219) ([hickford](https://github.com/hickford))

- Issue \#2211 -- splats in destructured parameters [\#2213](https://github.com/jashkenas/coffeescript/pull/2213) ([geraldalewis](https://github.com/geraldalewis))

- Support for =~ and !~ mapping to \[!\]/second/.test\(first\) [\#2311](https://github.com/jashkenas/coffeescript/pull/2311) ([karlseguin](https://github.com/karlseguin))

- Made a separate file where third-parties can add their extensions... [\#2286](https://github.com/jashkenas/coffeescript/pull/2286) ([bolinfest](https://github.com/bolinfest))

- Meaning of alias @ changed from 'this' to 'this.'. Keyword this keeps its... [\#2272](https://github.com/jashkenas/coffeescript/pull/2272) ([NoxArt](https://github.com/NoxArt))

- add travis-ci integration [\#2264](https://github.com/jashkenas/coffeescript/pull/2264) ([spaghetticode](https://github.com/spaghetticode))

- Add named classes that work in `use strict`. [\#2262](https://github.com/jashkenas/coffeescript/pull/2262) ([paulmillr](https://github.com/paulmillr))

- this != window in "Try CoffeeScript" [\#2260](https://github.com/jashkenas/coffeescript/pull/2260) ([josher19](https://github.com/josher19))

- new switch -g --shebang to prepend shebang to compiled Javascript [\#2222](https://github.com/jashkenas/coffeescript/pull/2222) ([hickford](https://github.com/hickford))

- build on Windows - fix spawn command [\#2220](https://github.com/jashkenas/coffeescript/pull/2220) ([hickford](https://github.com/hickford))

- Haskell-ish left arrow operator, async callbacks [\#2202](https://github.com/jashkenas/coffeescript/pull/2202) ([shf](https://github.com/shf))

## [1.3.1](https://github.com/jashkenas/coffeescript/tree/1.3.1) (2012-04-10)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/1.3.0...1.3.1)

**Closed issues:**

- 1.3.0 [\#2135](https://github.com/jashkenas/coffeescript/issues/2135)

- Executable class bodies, static inheritance, metaproggin'... [\#841](https://github.com/jashkenas/coffeescript/issues/841)

## [1.3.0](https://github.com/jashkenas/coffeescript/tree/1.3.0) (2012-04-10)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/1.2.0...1.3.0)

**Implemented enhancements:**

- Usage of names like `Array` for local variables is restricted [\#2208](https://github.com/jashkenas/coffeescript/issues/2208)

- Calling super\(\) inside non-class methods [\#2156](https://github.com/jashkenas/coffeescript/issues/2156)

- Allow the use of == using like operator [\#2093](https://github.com/jashkenas/coffeescript/issues/2093)

- dynamically appended coffee-scripts are not fetched [\#2041](https://github.com/jashkenas/coffeescript/issues/2041)

- Add support for multi-line input in REPL [\#1979](https://github.com/jashkenas/coffeescript/issues/1979)

- Possibly bring back closed over variables in loops. [\#1804](https://github.com/jashkenas/coffeescript/issues/1804)

- class then 'use strict' [\#1534](https://github.com/jashkenas/coffeescript/issues/1534)

- Flag to Disable "\_\_" Helper Functions [\#1494](https://github.com/jashkenas/coffeescript/issues/1494)

- className property on class objects [\#494](https://github.com/jashkenas/coffeescript/issues/494)

**Fixed bugs:**

- Top-level comments in REPL [\#2239](https://github.com/jashkenas/coffeescript/issues/2239)

- 0x0b0 [\#2224](https://github.com/jashkenas/coffeescript/issues/2224)

- Wrong interpretation involving property indentation [\#2221](https://github.com/jashkenas/coffeescript/issues/2221)

- CoffeeScript fails to report file and line where second constructor is defined [\#2206](https://github.com/jashkenas/coffeescript/issues/2206)

- npm link with cs binary script [\#2175](https://github.com/jashkenas/coffeescript/issues/2175)

- Watch + join + compile stops after 2 - 3 recompilations [\#2163](https://github.com/jashkenas/coffeescript/issues/2163)

- existential ?= operator causes weird behavior if setting to a closure [\#2155](https://github.com/jashkenas/coffeescript/issues/2155)

- Unhelpful/misleading Parse error Unexpected '{' when source has bad indents [\#2144](https://github.com/jashkenas/coffeescript/issues/2144)

- Continuation lines in REPL don't work as expected [\#2105](https://github.com/jashkenas/coffeescript/issues/2105)

- Only first file fed to compiler is wrapped; the rest are bare [\#2067](https://github.com/jashkenas/coffeescript/issues/2067)

- Destructuring fails with `new` due to operator precedence [\#2055](https://github.com/jashkenas/coffeescript/issues/2055)

- {eval} [\#2054](https://github.com/jashkenas/coffeescript/issues/2054)

- -\> \#\#\# \#\#\#; x [\#2037](https://github.com/jashkenas/coffeescript/issues/2037)

- piped input to REPL throws error [\#2001](https://github.com/jashkenas/coffeescript/issues/2001)

- TypeError: Cannot call method 'push' of undefined [\#1980](https://github.com/jashkenas/coffeescript/issues/1980)

- REPL is buggy [\#1976](https://github.com/jashkenas/coffeescript/issues/1976)

- Use of Array.prototype for \_\_slice throws on Array declaration [\#1973](https://github.com/jashkenas/coffeescript/issues/1973)

- syntax regression with compound assignment against implicit object in 1.2.0 [\#1961](https://github.com/jashkenas/coffeescript/issues/1961)

- coffee --watch stops detecting changes to files [\#1853](https://github.com/jashkenas/coffeescript/issues/1853)

- pipe\(\): Too many open files [\#1537](https://github.com/jashkenas/coffeescript/issues/1537)

- Inherited Class generated code does not match order of execution [\#1455](https://github.com/jashkenas/coffeescript/issues/1455)

- Significant last semicolon in a one liner function [\#1195](https://github.com/jashkenas/coffeescript/issues/1195)

- `coffee -w -j` exits after first run [\#1075](https://github.com/jashkenas/coffeescript/issues/1075)

**Closed issues:**

- CoffeeScript.eval should have bare: on by default in the browser [\#2148](https://github.com/jashkenas/coffeescript/issues/2148)

- In help, clarify how to pass args to the script [\#2120](https://github.com/jashkenas/coffeescript/issues/2120)

- Disallow Uppercase Radix Prefixes? [\#2060](https://github.com/jashkenas/coffeescript/issues/2060)

- Any way to store only coffee files in npm projects? [\#1977](https://github.com/jashkenas/coffeescript/issues/1977)

- Leaky abstraction in dynamically assigned constructor functions [\#1966](https://github.com/jashkenas/coffeescript/issues/1966)

- ?= assignment in closure declares variable globally [\#1627](https://github.com/jashkenas/coffeescript/issues/1627)

- Improve `do` \(x = y\) -\>` and support `do \(x\) -\>` [\#960](https://github.com/jashkenas/coffeescript/issues/960)

**Merged pull requests:**

- add --help indicator for passing arguments to scripts run with `coffee` [\#2121](https://github.com/jashkenas/coffeescript/pull/2121) ([michaelficarra](https://github.com/michaelficarra))

- Improve documentation section about heregexes [\#2117](https://github.com/jashkenas/coffeescript/pull/2117) ([ghost](https://github.com/ghost))

- Fix a confusing error message for '\(arguments\) -\>' [\#2116](https://github.com/jashkenas/coffeescript/pull/2116) ([jakub-](https://github.com/jakub-))

- Issue \#2105 [\#2106](https://github.com/jashkenas/coffeescript/pull/2106) ([kengregson](https://github.com/kengregson))

- Fix inherited spelling in documentation [\#2102](https://github.com/jashkenas/coffeescript/pull/2102) ([Nitrodist](https://github.com/Nitrodist))

- Style fixes [\#2101](https://github.com/jashkenas/coffeescript/pull/2101) ([clutchski](https://github.com/clutchski))

- Documenting default slice indexes. [\#2070](https://github.com/jashkenas/coffeescript/pull/2070) ([clutchski](https://github.com/clutchski))

- Lint fixes [\#2062](https://github.com/jashkenas/coffeescript/pull/2062) ([clutchski](https://github.com/clutchski))

- Issue \#2060 Disallow uppercase radix prefixes and exponential notation [\#2061](https://github.com/jashkenas/coffeescript/pull/2061) ([geraldalewis](https://github.com/geraldalewis))

- Issue \#2054 "{arguments}" [\#2057](https://github.com/jashkenas/coffeescript/pull/2057) ([geraldalewis](https://github.com/geraldalewis))

- Hex-escaped bell char for error on --watched compilation [\#2049](https://github.com/jashkenas/coffeescript/pull/2049) ([jawj](https://github.com/jawj))

- Changed octal to decimal for escaped bell character [\#2048](https://github.com/jashkenas/coffeescript/pull/2048) ([jawj](https://github.com/jawj))

- \#1534 class then "use strict" [\#2033](https://github.com/jashkenas/coffeescript/pull/2033) ([geraldalewis](https://github.com/geraldalewis))

- Cake::printTasks broken in node v0.4 [\#2011](https://github.com/jashkenas/coffeescript/pull/2011) ([zzen](https://github.com/zzen))

- Parse error when returning object literals from array/object comprehensions [\#2007](https://github.com/jashkenas/coffeescript/pull/2007) ([rolftimmermans](https://github.com/rolftimmermans))

- fixes \#2001: spoof a REPL readline interface to handle piped REPL input [\#2003](https://github.com/jashkenas/coffeescript/pull/2003) ([michaelficarra](https://github.com/michaelficarra))

- fixes \#1966: external constructors should produce their return value [\#1970](https://github.com/jashkenas/coffeescript/pull/1970) ([michaelficarra](https://github.com/michaelficarra))

- Rewatch files on change event \(redo\) [\#1964](https://github.com/jashkenas/coffeescript/pull/1964) ([TrevorBurnham](https://github.com/TrevorBurnham))

- fixes \#1910: loop index should be mutable within a loop iteration and immutable between loop iterations [\#1959](https://github.com/jashkenas/coffeescript/pull/1959) ([michaelficarra](https://github.com/michaelficarra))

- Seperated Books and Screencasts and added Code School course [\#1956](https://github.com/jashkenas/coffeescript/pull/1956) ([Gregg](https://github.com/Gregg))

- Allowing both end-points of slices to be implicit. [\#1955](https://github.com/jashkenas/coffeescript/pull/1955) ([clutchski](https://github.com/clutchski))

- Added --beep option to command, to warn user on compilation failure with --watch [\#1953](https://github.com/jashkenas/coffeescript/pull/1953) ([jawj](https://github.com/jawj))

- Adding header to generated JS \(\#1778\) [\#1793](https://github.com/jashkenas/coffeescript/pull/1793) ([TrevorBurnham](https://github.com/TrevorBurnham))

- Prohibit conditional assignment of undefined variables \(\#1627\) [\#1729](https://github.com/jashkenas/coffeescript/pull/1729) ([jeremybanks](https://github.com/jeremybanks))

- coffee -l should try to use both 'jsl' and 'jslint' commands [\#2228](https://github.com/jashkenas/coffeescript/pull/2228) ([rma4ok](https://github.com/rma4ok))

- When odd number representations are used, preserve original in comment [\#2226](https://github.com/jashkenas/coffeescript/pull/2226) ([michaelficarra](https://github.com/michaelficarra))

- Add attr\_reader, attr\_writer and attr\_accessor properties [\#2173](https://github.com/jashkenas/coffeescript/pull/2173) ([itrelease](https://github.com/itrelease))

- Same result for different index... [\#2147](https://github.com/jashkenas/coffeescript/pull/2147) ([itrelease](https://github.com/itrelease))

- Package definitions [\#2087](https://github.com/jashkenas/coffeescript/pull/2087) ([ich](https://github.com/ich))

- this patch adds syntax to coffeescript for object attribute access with a default [\#2058](https://github.com/jashkenas/coffeescript/pull/2058) ([andrewrk](https://github.com/andrewrk))

- Fixed typo in documentation [\#2038](https://github.com/jashkenas/coffeescript/pull/2038) ([chip](https://github.com/chip))

- Fixes \#2001: Allow piped input to coffee [\#2002](https://github.com/jashkenas/coffeescript/pull/2002) ([TrevorBurnham](https://github.com/TrevorBurnham))

- First step source source file mapping [\#2000](https://github.com/jashkenas/coffeescript/pull/2000) ([rtsuk](https://github.com/rtsuk))

- make repl scopes match script scopes [\#1995](https://github.com/jashkenas/coffeescript/pull/1995) ([codelahoma](https://github.com/codelahoma))

- Default constructor for subclass now returns returned value from parent [\#1975](https://github.com/jashkenas/coffeescript/pull/1975) ([rymohr](https://github.com/rymohr))

- Fixing \#1023 by moving compiler events from command to coffee-script [\#1968](https://github.com/jashkenas/coffeescript/pull/1968) ([TrevorBurnham](https://github.com/TrevorBurnham))

- Fire event after coffee scripts are all loaded in the browser [\#1967](https://github.com/jashkenas/coffeescript/pull/1967) ([JustinTulloss](https://github.com/JustinTulloss))

- Rewatch files on change event [\#1963](https://github.com/jashkenas/coffeescript/pull/1963) ([TrevorBurnham](https://github.com/TrevorBurnham))

- fixes \#841: bring back the `extended` hook [\#1960](https://github.com/jashkenas/coffeescript/pull/1960) ([michaelficarra](https://github.com/michaelficarra))

- Travis CI integration [\#1946](https://github.com/jashkenas/coffeescript/pull/1946) ([clutchski](https://github.com/clutchski))

- fixes \#1721: CDATA support in text/coffeescript <script\> tags [\#1788](https://github.com/jashkenas/coffeescript/pull/1788) ([michaelficarra](https://github.com/michaelficarra))

- fixes \#1772: statically catch invalid regular expressions of any sort [\#1776](https://github.com/jashkenas/coffeescript/pull/1776) ([michaelficarra](https://github.com/michaelficarra))

- \#1002 identical params \(revised\) [\#1543](https://github.com/jashkenas/coffeescript/pull/1543) ([geraldalewis](https://github.com/geraldalewis))

- Fix for issue \#1455 - Inherited Class generated code does not match order of execution [\#1533](https://github.com/jashkenas/coffeescript/pull/1533) ([alanning](https://github.com/alanning))

## [1.2.0](https://github.com/jashkenas/coffeescript/tree/1.2.0) (2011-12-18)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/1.1.3...1.2.0)

**Implemented enhancements:**

- Enhance --watch to pick up new files... [\#1941](https://github.com/jashkenas/coffeescript/issues/1941)

- Crash when calling cake --help [\#1862](https://github.com/jashkenas/coffeescript/issues/1862)

- Possibly add simplified contracts [\#1833](https://github.com/jashkenas/coffeescript/issues/1833)

- .clear command for coffee REPL [\#1672](https://github.com/jashkenas/coffeescript/issues/1672)

**Fixed bugs:**

- compiler options cannot be reused [\#1924](https://github.com/jashkenas/coffeescript/issues/1924)

- 1.1.3 regression? "Unexpected 'CALL\_END'" error on inline assignment expression [\#1922](https://github.com/jashkenas/coffeescript/issues/1922)

- Linebreak inserted before shebang in compiled output with CoffeeScript 1.1.3 [\#1911](https://github.com/jashkenas/coffeescript/issues/1911)

- class @A extends A [\#1876](https://github.com/jashkenas/coffeescript/issues/1876)

- Extra \_ref variable created for no reason [\#1861](https://github.com/jashkenas/coffeescript/issues/1861)

- 1 if -\> [\#1859](https://github.com/jashkenas/coffeescript/issues/1859)

- Global return should always generate safety closure  [\#1858](https://github.com/jashkenas/coffeescript/issues/1858)

- inconsistency with pure statement and \(nested\) comprehensions [\#1850](https://github.com/jashkenas/coffeescript/issues/1850)

- Parse error on line NaN: Unexpected 'MATH' [\#1848](https://github.com/jashkenas/coffeescript/issues/1848)

- f try =\> [\#1844](https://github.com/jashkenas/coffeescript/issues/1844)

- New binding implementation scope issue [\#1842](https://github.com/jashkenas/coffeescript/issues/1842)

- Referencing the prototype of a function call results in a TypeError \(1.1.3\) [\#1840](https://github.com/jashkenas/coffeescript/issues/1840)

- Variable declaration with newlines broken in 1.1.3 [\#1838](https://github.com/jashkenas/coffeescript/issues/1838)

- Class-related syntax errors [\#1813](https://github.com/jashkenas/coffeescript/issues/1813)

- PARSE ERROR ON LINE NAN: UNEXPECTED 'STRING' [\#1379](https://github.com/jashkenas/coffeescript/issues/1379)

- Parse error on line NaN [\#1148](https://github.com/jashkenas/coffeescript/issues/1148)

- implicit object nesting [\#1116](https://github.com/jashkenas/coffeescript/issues/1116)

**Closed issues:**

- @func inside a class definition captures next line as argument [\#1903](https://github.com/jashkenas/coffeescript/issues/1903)

- Top-level block comment is compiled inside of safety wrapper [\#1509](https://github.com/jashkenas/coffeescript/issues/1509)

**Merged pull requests:**

- Misc fixes for --watch [\#1944](https://github.com/jashkenas/coffeescript/pull/1944) ([TrevorBurnham](https://github.com/TrevorBurnham))

- Mark implicit parens generated [\#1943](https://github.com/jashkenas/coffeescript/pull/1943) ([clutchski](https://github.com/clutchski))

- reverting to 26a28ab behaviour [\#1938](https://github.com/jashkenas/coffeescript/pull/1938) ([michaelficarra](https://github.com/michaelficarra))

- Documentation fix: s/traverse/traverseChildren/ [\#1927](https://github.com/jashkenas/coffeescript/pull/1927) ([clutchski](https://github.com/clutchski))

- jison 0.2.11 requires node v0.4 - v0.5 [\#1916](https://github.com/jashkenas/coffeescript/pull/1916) ([ded](https://github.com/ded))

- Two tiny fixes [\#1892](https://github.com/jashkenas/coffeescript/pull/1892) ([marijnh](https://github.com/marijnh))

- Document fat arrow in class definitions. [\#1888](https://github.com/jashkenas/coffeescript/pull/1888) ([joliss](https://github.com/joliss))

- Use "index" for index variable in for loop [\#1887](https://github.com/jashkenas/coffeescript/pull/1887) ([joliss](https://github.com/joliss))

- \#1840 Invocation Prototype Prop Access [\#1868](https://github.com/jashkenas/coffeescript/pull/1868) ([geraldalewis](https://github.com/geraldalewis))

- Interface enhancements for cake \(\#1862\) [\#1866](https://github.com/jashkenas/coffeescript/pull/1866) ([TrevorBurnham](https://github.com/TrevorBurnham))

- fixes \#1844: bound functions in nested comprehensions causing empty var statements [\#1851](https://github.com/jashkenas/coffeescript/pull/1851) ([michaelficarra](https://github.com/michaelficarra))

- Re-fs.watching files on rename event [\#1847](https://github.com/jashkenas/coffeescript/pull/1847) ([TrevorBurnham](https://github.com/TrevorBurnham))

- update link [\#1845](https://github.com/jashkenas/coffeescript/pull/1845) ([joliss](https://github.com/joliss))

- fixes \#1832: speed up `CoffeeScript.eval` in browser script [\#1839](https://github.com/jashkenas/coffeescript/pull/1839) ([michaelficarra](https://github.com/michaelficarra))

- split out Usage section [\#1697](https://github.com/jashkenas/coffeescript/pull/1697) ([showell](https://github.com/showell))

- Issue \#1896: a: func b, {c: d} [\#1912](https://github.com/jashkenas/coffeescript/pull/1912) ([jiangmiao](https://github.com/jiangmiao))

- Using fs.watchFile if supported, fs.watch otherwise \(fixes \#1803\) [\#1846](https://github.com/jashkenas/coffeescript/pull/1846) ([TrevorBurnham](https://github.com/TrevorBurnham))

- fixes \#1771 [\#1777](https://github.com/jashkenas/coffeescript/pull/1777) ([michaelficarra](https://github.com/michaelficarra))

- Added instructions on how to run on windows [\#1745](https://github.com/jashkenas/coffeescript/pull/1745) ([JulianBirch](https://github.com/JulianBirch))

- Add documentation on executing .coffee scripts [\#1516](https://github.com/jashkenas/coffeescript/pull/1516) ([barberboy](https://github.com/barberboy))

- Making `-c` and `-o` flags orthogonal [\#1327](https://github.com/jashkenas/coffeescript/pull/1327) ([TrevorBurnham](https://github.com/TrevorBurnham))

## [1.1.3](https://github.com/jashkenas/coffeescript/tree/1.1.3) (2011-11-08)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/1.1.2...1.1.3)

**Implemented enhancements:**

- Move helpers within local scope if possible [\#1779](https://github.com/jashkenas/coffeescript/issues/1779)

- CLI: filenames beginning with `-` [\#1754](https://github.com/jashkenas/coffeescript/issues/1754)

- website: break out "Usage" and lead with examples [\#1695](https://github.com/jashkenas/coffeescript/issues/1695)

- further refine command-line help [\#1682](https://github.com/jashkenas/coffeescript/issues/1682)

- View definitions in REPL [\#1583](https://github.com/jashkenas/coffeescript/issues/1583)

- class C\_NAME extends require "C\_EXPORTING\_MODULE" ? [\#1482](https://github.com/jashkenas/coffeescript/issues/1482)

- improve `when` compilation [\#1254](https://github.com/jashkenas/coffeescript/issues/1254)

- create coffee-script.js flattened node.js library? [\#1246](https://github.com/jashkenas/coffeescript/issues/1246)

- Multi-Line Comments ends with a new line [\#1186](https://github.com/jashkenas/coffeescript/issues/1186)

- Independent splats in array pattern matching [\#870](https://github.com/jashkenas/coffeescript/issues/870)

- Tuning soak compilation [\#756](https://github.com/jashkenas/coffeescript/issues/756)

**Fixed bugs:**

- node\_stdio was removed from Node v0.5.10 [\#1798](https://github.com/jashkenas/coffeescript/issues/1798)

- Destructuring assignment issue [\#1794](https://github.com/jashkenas/coffeescript/issues/1794)

- odd object literal behavior [\#1747](https://github.com/jashkenas/coffeescript/issues/1747)

-  continuation backslash bug [\#1725](https://github.com/jashkenas/coffeescript/issues/1725)

- /\*/ [\#1724](https://github.com/jashkenas/coffeescript/issues/1724)

- a\[..b or c\] = d [\#1723](https://github.com/jashkenas/coffeescript/issues/1723)

- a\[..b or c\] [\#1722](https://github.com/jashkenas/coffeescript/issues/1722)

- coffee -bpe "2 for \[1..2\]; a in b" fails [\#1714](https://github.com/jashkenas/coffeescript/issues/1714)

- - --x [\#1703](https://github.com/jashkenas/coffeescript/issues/1703)

- Parse error on close parens [\#1680](https://github.com/jashkenas/coffeescript/issues/1680)

- break/continue make all list comprehensions \[\] [\#1669](https://github.com/jashkenas/coffeescript/issues/1669)

- An old bug [\#1656](https://github.com/jashkenas/coffeescript/issues/1656)

- Compiler: Destructured Assignment + Splat + Object.key [\#1643](https://github.com/jashkenas/coffeescript/issues/1643)

- throwing non-Error value from executed \*.coffee [\#1633](https://github.com/jashkenas/coffeescript/issues/1633)

- `in` test JScript compatibility [\#1630](https://github.com/jashkenas/coffeescript/issues/1630)

- Support `super` in static/class methods? [\#1598](https://github.com/jashkenas/coffeescript/issues/1598)

- Reusing a variable in a catch\(\) expression makes the variable undeclared [\#1595](https://github.com/jashkenas/coffeescript/issues/1595)

- splatted expressions in destructuring assignment [\#1591](https://github.com/jashkenas/coffeescript/issues/1591)

- Object literals nest unexpectedly [\#1577](https://github.com/jashkenas/coffeescript/issues/1577)

- new super [\#1568](https://github.com/jashkenas/coffeescript/issues/1568)

- Test Failures [\#1562](https://github.com/jashkenas/coffeescript/issues/1562)

- A::\[1..5\] produces wrong code [\#1554](https://github.com/jashkenas/coffeescript/issues/1554)

- {}? [\#1513](https://github.com/jashkenas/coffeescript/issues/1513)

- Static fat functions don't keep context [\#1464](https://github.com/jashkenas/coffeescript/issues/1464)

- Unmatched braces [\#1299](https://github.com/jashkenas/coffeescript/issues/1299)

- Applying a splat to a prototype using the short syntax applies the splat to the wrong object [\#1234](https://github.com/jashkenas/coffeescript/issues/1234)

- continued line and assignment [\#1110](https://github.com/jashkenas/coffeescript/issues/1110)

- String literal prevents line continuation [\#1102](https://github.com/jashkenas/coffeescript/issues/1102)

- \[f\(\)...\] = a [\#1101](https://github.com/jashkenas/coffeescript/issues/1101)

- x in \[a, b or c\] [\#1100](https://github.com/jashkenas/coffeescript/issues/1100)

- class @do [\#1009](https://github.com/jashkenas/coffeescript/issues/1009)

- invalid identifiers allowed on LHS of destructuring assignment [\#1005](https://github.com/jashkenas/coffeescript/issues/1005)

**Closed issues:**

- Node:  use fs.watch api instead [\#1803](https://github.com/jashkenas/coffeescript/issues/1803)

- Suggestion: Put Windows Instructions in README [\#1741](https://github.com/jashkenas/coffeescript/issues/1741)

- selection\_sort.coffee is broken [\#1699](https://github.com/jashkenas/coffeescript/issues/1699)

- Check parent directories for Cakefiles [\#1686](https://github.com/jashkenas/coffeescript/issues/1686)

- 1.1.2 point release: motivation thread [\#1561](https://github.com/jashkenas/coffeescript/issues/1561)

- Speed hit on version 1.1.1 when using --join [\#1397](https://github.com/jashkenas/coffeescript/issues/1397)

**Merged pull requests:**

- Added AMD support. [\#1826](https://github.com/jashkenas/coffeescript/pull/1826) ([samcday](https://github.com/samcday))

- fixes \#1798: using process.stderr in command.coffee [\#1807](https://github.com/jashkenas/coffeescript/pull/1807) ([TrevorBurnham](https://github.com/TrevorBurnham))

- Using console.log and console.error in command.coffee \(\#1798\) [\#1801](https://github.com/jashkenas/coffeescript/pull/1801) ([TrevorBurnham](https://github.com/TrevorBurnham))

- Binary notation integers \(0b100 as 4\). [\#1787](https://github.com/jashkenas/coffeescript/pull/1787) ([revence27](https://github.com/revence27))

- Add flag to surpress color in cake output [\#1757](https://github.com/jashkenas/coffeescript/pull/1757) ([disnet](https://github.com/disnet))

- Upgrade jQuery in documentation from v1.4.2 to v1.6.4 [\#1719](https://github.com/jashkenas/coffeescript/pull/1719) ([jeremybanks](https://github.com/jeremybanks))

- Add a \[Link\] button to the "Try CoffeeScript" interface [\#1711](https://github.com/jashkenas/coffeescript/pull/1711) ([jeremybanks](https://github.com/jeremybanks))

- I didn't see an example of how to do this and thought it might be helpful for others. [\#1691](https://github.com/jashkenas/coffeescript/pull/1691) ([willbailey](https://github.com/willbailey))

- Check parent directories for Cakefiles [\#1687](https://github.com/jashkenas/coffeescript/pull/1687) ([fortes](https://github.com/fortes))

- clarify --watch option in "coffee -h" output [\#1673](https://github.com/jashkenas/coffeescript/pull/1673) ([codelahoma](https://github.com/codelahoma))

- \#1643 splatted access [\#1666](https://github.com/jashkenas/coffeescript/pull/1666) ([geraldalewis](https://github.com/geraldalewis))

- Bump node dependency from 0.2.5 to 0.4.0 [\#1663](https://github.com/jashkenas/coffeescript/pull/1663) ([TrevorBurnham](https://github.com/TrevorBurnham))

- \#1195 Ignore trailing semicolons [\#1662](https://github.com/jashkenas/coffeescript/pull/1662) ([geraldalewis](https://github.com/geraldalewis))

- Allow user-added globals on the REPL [\#1661](https://github.com/jashkenas/coffeescript/pull/1661) ([TrevorBurnham](https://github.com/TrevorBurnham))

- Adding a link to the change log to the current version on the webpage [\#1647](https://github.com/jashkenas/coffeescript/pull/1647) ([dget](https://github.com/dget))

- 1591 Splatted Expressions in Destructuring Assignment Must Be Assignable [\#1641](https://github.com/jashkenas/coffeescript/pull/1641) ([geraldalewis](https://github.com/geraldalewis))

- alert\(html\) in the heredoc example [\#1636](https://github.com/jashkenas/coffeescript/pull/1636) ([mineo](https://github.com/mineo))

- Enable Permalinking of Code in "Try CoffeeScript" [\#1628](https://github.com/jashkenas/coffeescript/pull/1628) ([jeremybanks](https://github.com/jeremybanks))

- Clarify `--watch` option on homepage.  [\#1625](https://github.com/jashkenas/coffeescript/pull/1625) ([codelahoma](https://github.com/codelahoma))

- --join fails silently with no resulting output file [\#1624](https://github.com/jashkenas/coffeescript/pull/1624) ([johnyanarella](https://github.com/johnyanarella))

- \#1513 Top level bare obj literals with unary and exist ops [\#1605](https://github.com/jashkenas/coffeescript/pull/1605) ([geraldalewis](https://github.com/geraldalewis))

- \#1234 Protoype Access in :: Operator [\#1590](https://github.com/jashkenas/coffeescript/pull/1590) ([geraldalewis](https://github.com/geraldalewis))

- fix path to grammar file [\#1584](https://github.com/jashkenas/coffeescript/pull/1584) ([MichaelBlume](https://github.com/MichaelBlume))

- Add uglify-js and jison as development dependencies [\#1576](https://github.com/jashkenas/coffeescript/pull/1576) ([sstephenson](https://github.com/sstephenson))

- 1464 bound static methods [\#1573](https://github.com/jashkenas/coffeescript/pull/1573) ([geraldalewis](https://github.com/geraldalewis))

- shorten one of the ternaries [\#1571](https://github.com/jashkenas/coffeescript/pull/1571) ([MichaelBlume](https://github.com/MichaelBlume))

- Using fs.watch instead of fs.watchFile under Windows \(fixes \#1803\) [\#1837](https://github.com/jashkenas/coffeescript/pull/1837) ([TrevorBurnham](https://github.com/TrevorBurnham))

- Support CRLF output for codegen of nodes. [\#1823](https://github.com/jashkenas/coffeescript/pull/1823) ([kellypleahy](https://github.com/kellypleahy))

- add callbacks for async chaining of tasks [\#1822](https://github.com/jashkenas/coffeescript/pull/1822) ([mental](https://github.com/mental))

- Binary Literals and Beautiful Literate Programming [\#1785](https://github.com/jashkenas/coffeescript/pull/1785) ([revence27](https://github.com/revence27))

- split out Usage section [\#1696](https://github.com/jashkenas/coffeescript/pull/1696) ([showell](https://github.com/showell))

- Command: Support for non-standard file extensions [\#1689](https://github.com/jashkenas/coffeescript/pull/1689) ([sabberworm](https://github.com/sabberworm))

- fixes \#1667 by decrementing the loop counter after a comprehension over a range [\#1670](https://github.com/jashkenas/coffeescript/pull/1670) ([michaelficarra](https://github.com/michaelficarra))

- Add Regexp operator =~ [\#1652](https://github.com/jashkenas/coffeescript/pull/1652) ([jiangmiao](https://github.com/jiangmiao))

- \#1195 Ignore trailing semicolons [\#1650](https://github.com/jashkenas/coffeescript/pull/1650) ([geraldalewis](https://github.com/geraldalewis))

- I add two new features about string. [\#1649](https://github.com/jashkenas/coffeescript/pull/1649) ([jiangmiao](https://github.com/jiangmiao))

- Extended --watch support [\#1634](https://github.com/jashkenas/coffeescript/pull/1634) ([dharmabruce](https://github.com/dharmabruce))

- Edited documentation/coffee/soaks.coffee via GitHub [\#1613](https://github.com/jashkenas/coffeescript/pull/1613) ([phiggins](https://github.com/phiggins))

- Worked on REPL a little, added some testing \(via command line only\) and ":exit" command to kill REPL [\#1566](https://github.com/jashkenas/coffeescript/pull/1566) ([parkerl](https://github.com/parkerl))

## [1.1.2](https://github.com/jashkenas/coffeescript/tree/1.1.2) (2011-08-05)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/1.1.1...1.1.2)

**Implemented enhancements:**

- consecutive semicolons [\#1492](https://github.com/jashkenas/coffeescript/issues/1492)

- concise way to check if value == null compiled into more readable javascript [\#1393](https://github.com/jashkenas/coffeescript/issues/1393)

- Default property values for options objects  [\#1373](https://github.com/jashkenas/coffeescript/issues/1373)

- Regexp in a switch [\#1370](https://github.com/jashkenas/coffeescript/issues/1370)

- Lexical scope and order [\#1121](https://github.com/jashkenas/coffeescript/issues/1121)

- Add Coda/SubEthaEdit syntax mode to resources list. [\#1085](https://github.com/jashkenas/coffeescript/issues/1085)

**Fixed bugs:**

- build:browser target is broken [\#1569](https://github.com/jashkenas/coffeescript/issues/1569)

- cake install problem [\#1541](https://github.com/jashkenas/coffeescript/issues/1541)

- --lint flag fails when using npm coffee-script package [\#1490](https://github.com/jashkenas/coffeescript/issues/1490)

- catch clause does not introduce a new scope [\#1467](https://github.com/jashkenas/coffeescript/issues/1467)

- Surprising compilation resulting from ?= [\#1461](https://github.com/jashkenas/coffeescript/issues/1461)

- Parse error: Unexpected 'FORIN' [\#1449](https://github.com/jashkenas/coffeescript/issues/1449)

- Compiler crashes on file-permission errors \(instead of useful warning message\) [\#1446](https://github.com/jashkenas/coffeescript/issues/1446)

- REPL changes context on each evaluation [\#1444](https://github.com/jashkenas/coffeescript/issues/1444)

- Line-counting bug when reporting parse error [\#1442](https://github.com/jashkenas/coffeescript/issues/1442)

- using 'for' as an object key results in Unexpected FOROF parse error if 'of' encountered afterward [\#1436](https://github.com/jashkenas/coffeescript/issues/1436)

- prototypes of literals in the REPL [\#1425](https://github.com/jashkenas/coffeescript/issues/1425)

- Error on REPL with implicit parens [\#1420](https://github.com/jashkenas/coffeescript/issues/1420)

- new new f a [\#1416](https://github.com/jashkenas/coffeescript/issues/1416)

- Range expressions \> 20 not working in REPL [\#1409](https://github.com/jashkenas/coffeescript/issues/1409)

- Comments in the REPL [\#1398](https://github.com/jashkenas/coffeescript/issues/1398)

- instanceof Array inconsistencies [\#1390](https://github.com/jashkenas/coffeescript/issues/1390)

- Function Invocation on a Number Literal Surrounded by Parentheses generates illegal JavaScript [\#1385](https://github.com/jashkenas/coffeescript/issues/1385)

- super and fancy method names [\#1380](https://github.com/jashkenas/coffeescript/issues/1380)

- Binding class methods with reserved names is broken [\#1372](https://github.com/jashkenas/coffeescript/issues/1372)

- Block comments error [\#1368](https://github.com/jashkenas/coffeescript/issues/1368)

- switch cannot be used as argument [\#1364](https://github.com/jashkenas/coffeescript/issues/1364)

- `in` and splatted array [\#1354](https://github.com/jashkenas/coffeescript/issues/1354)

- ++ -- operations bug [\#1352](https://github.com/jashkenas/coffeescript/issues/1352)

- super and dollar [\#1328](https://github.com/jashkenas/coffeescript/issues/1328)

- `by` value is uncached [\#1326](https://github.com/jashkenas/coffeescript/issues/1326)

- Regression: Mixing block comments and object params [\#1322](https://github.com/jashkenas/coffeescript/issues/1322)

- Regression with list comprehensions and `this` [\#1318](https://github.com/jashkenas/coffeescript/issues/1318)

- Arguments aren't scoped correctly when splatted [\#1315](https://github.com/jashkenas/coffeescript/issues/1315)

- String interpolation regression [\#1150](https://github.com/jashkenas/coffeescript/issues/1150)

- Extra semicolon in class method bind syntax [\#1072](https://github.com/jashkenas/coffeescript/issues/1072)

- REPL: script directory-relative requires fail with 'cannot find module' [\#1035](https://github.com/jashkenas/coffeescript/issues/1035)

**Closed issues:**

- Possible error in the documentation \(version 1.1.1\) [\#1478](https://github.com/jashkenas/coffeescript/issues/1478)

- ?= compilation [\#1216](https://github.com/jashkenas/coffeescript/issues/1216)

- Currently no way to match literal spaces in multiline regexps [\#1199](https://github.com/jashkenas/coffeescript/issues/1199)

**Merged pull requests:**

- Check for existence of this.context. Avoid build error. [\#1542](https://github.com/jashkenas/coffeescript/pull/1542) ([MichaelBlume](https://github.com/MichaelBlume))

- Fix for issue \#1446: Compiler fails with unrelated exception on file permissions problems [\#1527](https://github.com/jashkenas/coffeescript/pull/1527) ([breckinloggins](https://github.com/breckinloggins))

- Issue \#1470: Command line compiler now assumes ".coffee" extension if left off of file names [\#1522](https://github.com/jashkenas/coffeescript/pull/1522) ([breckinloggins](https://github.com/breckinloggins))

- Removed a garbage code in `pluckDirectCall`. [\#1518](https://github.com/jashkenas/coffeescript/pull/1518) ([taku0](https://github.com/taku0))

- Patch for issue \#1492 \(consecutive semicolons in compiled output\) [\#1517](https://github.com/jashkenas/coffeescript/pull/1517) ([breckinloggins](https://github.com/breckinloggins))

- Some typo corrections and minor documentation edits [\#1498](https://github.com/jashkenas/coffeescript/pull/1498) ([breckinloggins](https://github.com/breckinloggins))

- compileJoin should happen once after all files are read [\#1460](https://github.com/jashkenas/coffeescript/pull/1460) ([yyyc514](https://github.com/yyyc514))

- Issue1150 [\#1458](https://github.com/jashkenas/coffeescript/pull/1458) ([ngn](https://github.com/ngn))

- Bugfix for \#1416 [\#1450](https://github.com/jashkenas/coffeescript/pull/1450) ([thejh](https://github.com/thejh))

- Bugfix for \#1436, `for` etc. should work as normal property names [\#1448](https://github.com/jashkenas/coffeescript/pull/1448) ([thejh](https://github.com/thejh))

- promote the use of interpolation in the documentation [\#1426](https://github.com/jashkenas/coffeescript/pull/1426) ([michaelficarra](https://github.com/michaelficarra))

- 'coffee' silently fails with no output when the --join option is specified and the source files specified include directories [\#1388](https://github.com/jashkenas/coffeescript/pull/1388) ([johnyanarella](https://github.com/johnyanarella))

- 1216 1348 [\#1353](https://github.com/jashkenas/coffeescript/pull/1353) ([geraldalewis](https://github.com/geraldalewis))

- Fix for \#1216 ?= compilation [\#1348](https://github.com/jashkenas/coffeescript/pull/1348) ([geraldalewis](https://github.com/geraldalewis))

- Fixed improper scoping of siblings to the splat argument. [\#1346](https://github.com/jashkenas/coffeescript/pull/1346) ([sparecycles](https://github.com/sparecycles))

- Use `require.main` instead of loop to get main module [\#1324](https://github.com/jashkenas/coffeescript/pull/1324) ([TrevorBurnham](https://github.com/TrevorBurnham))

- \#1464 Bound Static Methods [\#1572](https://github.com/jashkenas/coffeescript/pull/1572) ([geraldalewis](https://github.com/geraldalewis))

- \#1002 identical params [\#1531](https://github.com/jashkenas/coffeescript/pull/1531) ([geraldalewis](https://github.com/geraldalewis))

- Fix for issue \#1446: Provide meaningful error message for file access problems [\#1526](https://github.com/jashkenas/coffeescript/pull/1526) ([breckinloggins](https://github.com/breckinloggins))

- Corrected example to correctly refer to grade, instead of eldest. [\#1501](https://github.com/jashkenas/coffeescript/pull/1501) ([deadprogram](https://github.com/deadprogram))

- Fix for \#1035: Giving the `eval` sandbox a real `Module` instance [\#1487](https://github.com/jashkenas/coffeescript/pull/1487) ([TrevorBurnham](https://github.com/TrevorBurnham))

- Catch creates its own shared scope. [\#1476](https://github.com/jashkenas/coffeescript/pull/1476) ([taku0](https://github.com/taku0))

- add other javascript keywords [\#1474](https://github.com/jashkenas/coffeescript/pull/1474) ([ryankshaw](https://github.com/ryankshaw))

- Debug mode for running .coffee scripts \#558, \#987 [\#1396](https://github.com/jashkenas/coffeescript/pull/1396) ([geraldalewis](https://github.com/geraldalewis))

- after heregexps line numbers are broken [\#1374](https://github.com/jashkenas/coffeescript/pull/1374) ([fjakobs](https://github.com/fjakobs))

- added an ask method to the cake lib [\#1357](https://github.com/jashkenas/coffeescript/pull/1357) ([twilson63](https://github.com/twilson63))

- Fixed improper scoping of siblings to the splat argument. [\#1336](https://github.com/jashkenas/coffeescript/pull/1336) ([sparecycles](https://github.com/sparecycles))

- Allow `CoffeeScript.eval` to return its result when `bare` is not set [\#1314](https://github.com/jashkenas/coffeescript/pull/1314) ([TrevorBurnham](https://github.com/TrevorBurnham))

## [1.1.1](https://github.com/jashkenas/coffeescript/tree/1.1.1) (2011-05-10)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/1.1.0...1.1.1)

**Fixed bugs:**

- Extends and constructor lead to disappearing property \(regression\) [\#1313](https://github.com/jashkenas/coffeescript/issues/1313)

- `extends` and external constructor [\#1182](https://github.com/jashkenas/coffeescript/issues/1182)

**Merged pull requests:**

- Patch for Issue \#1326 `by` value is uncached [\#1330](https://github.com/jashkenas/coffeescript/pull/1330) ([geraldalewis](https://github.com/geraldalewis))

- Tagged the pull request [\#1337](https://github.com/jashkenas/coffeescript/pull/1337) ([sparecycles](https://github.com/sparecycles))

- Optimization of parser.js [\#1321](https://github.com/jashkenas/coffeescript/pull/1321) ([joshnur](https://github.com/joshnur))

- Potential fix for \#1313: Extends and constructor lead to disappearing pro [\#1320](https://github.com/jashkenas/coffeescript/pull/1320) ([ef4](https://github.com/ef4))

## [1.1.0](https://github.com/jashkenas/coffeescript/tree/1.1.0) (2011-05-01)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/1.0.1...1.1.0)

**Implemented enhancements:**

- 1-element array just prints the only item, which is misleading [\#1266](https://github.com/jashkenas/coffeescript/issues/1266)

- Using extends apart from class declaration [\#1258](https://github.com/jashkenas/coffeescript/issues/1258)

- pragmas [\#1231](https://github.com/jashkenas/coffeescript/issues/1231)

- Destructuring Compound Assignment [\#1226](https://github.com/jashkenas/coffeescript/issues/1226)

- "Zen" of CoffeeScript [\#1221](https://github.com/jashkenas/coffeescript/issues/1221)

- Compile anonymous functions without unused implicit returns [\#1134](https://github.com/jashkenas/coffeescript/issues/1134)

- Allow user to define name of concatenation JS file. [\#1076](https://github.com/jashkenas/coffeescript/issues/1076)

**Fixed bugs:**

- proccess.argv is wrong [\#1301](https://github.com/jashkenas/coffeescript/issues/1301)

- compile fails to check error in fs.stat callback, crashes [\#1294](https://github.com/jashkenas/coffeescript/issues/1294)

- a /= b / c [\#1280](https://github.com/jashkenas/coffeescript/issues/1280)

- `{} = a\(\)` compiles to `false;` [\#1274](https://github.com/jashkenas/coffeescript/issues/1274)

- print filename in error messages when requiring .coffee files [\#1262](https://github.com/jashkenas/coffeescript/issues/1262)

- small typo in docu: docs -\> dots [\#1256](https://github.com/jashkenas/coffeescript/issues/1256)

- for x in y by -1 [\#1208](https://github.com/jashkenas/coffeescript/issues/1208)

- Scope for self-referencing functions [\#1188](https://github.com/jashkenas/coffeescript/issues/1188)

- coffee doesn't seem to honor ../node\_modules [\#1173](https://github.com/jashkenas/coffeescript/issues/1173)

- Compiler silently fails when concatenating files of which one is an empty file [\#1157](https://github.com/jashkenas/coffeescript/issues/1157)

- For index not renamed on collision [\#1124](https://github.com/jashkenas/coffeescript/issues/1124)

- \_\_proto\_\_ [\#1106](https://github.com/jashkenas/coffeescript/issues/1106)

- \[\[\]\] = f\(\) [\#1103](https://github.com/jashkenas/coffeescript/issues/1103)

- Slow compilation with long method chains [\#1033](https://github.com/jashkenas/coffeescript/issues/1033)

- infinite loop somewhere in rewriter [\#1006](https://github.com/jashkenas/coffeescript/issues/1006)

- Bug with chained comparisons and existential accessor [\#908](https://github.com/jashkenas/coffeescript/issues/908)

**Closed issues:**

- Can we please start a user discussion group? [\#1276](https://github.com/jashkenas/coffeescript/issues/1276)

- Improve REPL output for loops [\#1109](https://github.com/jashkenas/coffeescript/issues/1109)

**Merged pull requests:**

- Fixing unavailability of `global` properties on REPL [\#1309](https://github.com/jashkenas/coffeescript/pull/1309) ([TrevorBurnham](https://github.com/TrevorBurnham))

- Set `process.execPath` correctly when running .coffee files [\#1307](https://github.com/jashkenas/coffeescript/pull/1307) ([TrevorBurnham](https://github.com/TrevorBurnham))

- Updated for npm 1.0: the -g option installs to the global npm bin directory [\#1305](https://github.com/jashkenas/coffeescript/pull/1305) ([benatkin](https://github.com/benatkin))

- Set process.argv\[0\] to 'coffee' when using `coffee foo.coffee` [\#1303](https://github.com/jashkenas/coffeescript/pull/1303) ([TrevorBurnham](https://github.com/TrevorBurnham))

- fixes issue \#1106 [\#1300](https://github.com/jashkenas/coffeescript/pull/1300) ([michaelficarra](https://github.com/michaelficarra))

- Typo error, s/synax/syntax [\#1298](https://github.com/jashkenas/coffeescript/pull/1298) ([pjaspers](https://github.com/pjaspers))

- Enforce script execution order in `browser.coffee`. [\#1277](https://github.com/jashkenas/coffeescript/pull/1277) ([kitcambridge](https://github.com/kitcambridge))

- fixes \#1157: when compiling multiple scripts, compile them if at least on [\#1245](https://github.com/jashkenas/coffeescript/pull/1245) ([thejh](https://github.com/thejh))

- Fix node\_modules requires from interpreted .coffee files [\#1233](https://github.com/jashkenas/coffeescript/pull/1233) ([josh](https://github.com/josh))

- Keyboard shortcuts for Try Coffeescript [\#1127](https://github.com/jashkenas/coffeescript/pull/1127) ([willmoffat](https://github.com/willmoffat))

- Alternative script loading fix [\#1306](https://github.com/jashkenas/coffeescript/pull/1306) ([kitcambridge](https://github.com/kitcambridge))

- Hi guys, just 2 minor additions to index.html [\#1295](https://github.com/jashkenas/coffeescript/pull/1295) ([ghost](https://github.com/ghost))

- fixes bug mentioned by @satyr in \#1108 [\#1243](https://github.com/jashkenas/coffeescript/pull/1243) ([thejh](https://github.com/thejh))

- fixes \#1099: instead of nothing, compile to false [\#1242](https://github.com/jashkenas/coffeescript/pull/1242) ([thejh](https://github.com/thejh))

- object unpacking defaults [\#1227](https://github.com/jashkenas/coffeescript/pull/1227) ([thejh](https://github.com/thejh))

- Improved range compilation [\#1224](https://github.com/jashkenas/coffeescript/pull/1224) ([michaelficarra](https://github.com/michaelficarra))

- Ensure that CoffeeScript is run in consistent order in the browser [\#1058](https://github.com/jashkenas/coffeescript/pull/1058) ([TrevorBurnham](https://github.com/TrevorBurnham))

## [1.0.1](https://github.com/jashkenas/coffeescript/tree/1.0.1) (2011-02-01)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/1.0.0...1.0.1)

## [1.0.0](https://github.com/jashkenas/coffeescript/tree/1.0.0) (2010-12-24)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.9.6...1.0.0)

## [0.9.6](https://github.com/jashkenas/coffeescript/tree/0.9.6) (2010-12-07)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.9.5...0.9.6)

## [0.9.5](https://github.com/jashkenas/coffeescript/tree/0.9.5) (2010-11-22)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.9.4...0.9.5)

## [0.9.4](https://github.com/jashkenas/coffeescript/tree/0.9.4) (2010-09-22)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.9.3...0.9.4)

## [0.9.3](https://github.com/jashkenas/coffeescript/tree/0.9.3) (2010-09-16)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.9.2...0.9.3)

## [0.9.2](https://github.com/jashkenas/coffeescript/tree/0.9.2) (2010-08-24)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.9.1...0.9.2)

## [0.9.1](https://github.com/jashkenas/coffeescript/tree/0.9.1) (2010-08-11)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.9.0...0.9.1)

## [0.9.0](https://github.com/jashkenas/coffeescript/tree/0.9.0) (2010-08-05)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.7.2...0.9.0)

## [0.7.2](https://github.com/jashkenas/coffeescript/tree/0.7.2) (2010-07-12)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.7.1...0.7.2)

## [0.7.1](https://github.com/jashkenas/coffeescript/tree/0.7.1) (2010-07-11)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.7.0...0.7.1)

## [0.7.0](https://github.com/jashkenas/coffeescript/tree/0.7.0) (2010-06-28)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.6.2...0.7.0)

## [0.6.2](https://github.com/jashkenas/coffeescript/tree/0.6.2) (2010-05-15)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.6.1...0.6.2)

## [0.6.1](https://github.com/jashkenas/coffeescript/tree/0.6.1) (2010-04-13)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.6.0...0.6.1)

## [0.6.0](https://github.com/jashkenas/coffeescript/tree/0.6.0) (2010-04-04)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.5.6...0.6.0)

## [0.5.6](https://github.com/jashkenas/coffeescript/tree/0.5.6) (2010-03-23)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.5.5...0.5.6)

## [0.5.5](https://github.com/jashkenas/coffeescript/tree/0.5.5) (2010-03-08)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.5.4...0.5.5)

## [0.5.4](https://github.com/jashkenas/coffeescript/tree/0.5.4) (2010-03-04)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.5.3...0.5.4)

## [0.5.3](https://github.com/jashkenas/coffeescript/tree/0.5.3) (2010-02-28)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.5.2...0.5.3)

## [0.5.2](https://github.com/jashkenas/coffeescript/tree/0.5.2) (2010-02-25)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.5.1...0.5.2)

## [0.5.1](https://github.com/jashkenas/coffeescript/tree/0.5.1) (2010-02-24)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.5.0...0.5.1)

## [0.5.0](https://github.com/jashkenas/coffeescript/tree/0.5.0) (2010-02-22)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.3.2...0.5.0)

## [0.3.2](https://github.com/jashkenas/coffeescript/tree/0.3.2) (2010-02-08)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.3.1...0.3.2)

## [0.3.1](https://github.com/jashkenas/coffeescript/tree/0.3.1) (2010-01-27)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.3.0...0.3.1)

## [0.3.0](https://github.com/jashkenas/coffeescript/tree/0.3.0) (2010-01-27)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.2.6...0.3.0)

## [0.2.6](https://github.com/jashkenas/coffeescript/tree/0.2.6) (2010-01-17)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.2.5...0.2.6)

## [0.2.5](https://github.com/jashkenas/coffeescript/tree/0.2.5) (2010-01-14)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.2.4...0.2.5)

## [0.2.4](https://github.com/jashkenas/coffeescript/tree/0.2.4) (2010-01-12)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.2.3...0.2.4)

## [0.2.3](https://github.com/jashkenas/coffeescript/tree/0.2.3) (2010-01-11)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.2.2...0.2.3)

## [0.2.2](https://github.com/jashkenas/coffeescript/tree/0.2.2) (2010-01-10)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.2.1...0.2.2)

## [0.2.1](https://github.com/jashkenas/coffeescript/tree/0.2.1) (2010-01-05)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.2.0...0.2.1)

## [0.2.0](https://github.com/jashkenas/coffeescript/tree/0.2.0) (2010-01-05)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.1.6...0.2.0)

## [0.1.6](https://github.com/jashkenas/coffeescript/tree/0.1.6) (2009-12-27)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.1.5...0.1.6)

## [0.1.5](https://github.com/jashkenas/coffeescript/tree/0.1.5) (2009-12-27)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.1.4...0.1.5)

## [0.1.4](https://github.com/jashkenas/coffeescript/tree/0.1.4) (2009-12-25)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.1.3...0.1.4)

## [0.1.3](https://github.com/jashkenas/coffeescript/tree/0.1.3) (2009-12-25)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.1.2...0.1.3)

## [0.1.2](https://github.com/jashkenas/coffeescript/tree/0.1.2) (2009-12-25)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.1.1...0.1.2)

## [0.1.1](https://github.com/jashkenas/coffeescript/tree/0.1.1) (2009-12-24)

[Full Changelog](https://github.com/jashkenas/coffeescript/compare/0.1.0...0.1.1)

## [0.1.0](https://github.com/jashkenas/coffeescript/tree/0.1.0) (2009-12-24)



\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*