# Awesome Rust Testing

**WANT TO HELP??** please help up by adding more things or even better: evaluating the things on the list
* Are the things still maintained? Can we add badges here? short descriptions? Quality Control

## Books
* [awesome-mdbook (general)](https://github.com/softprops/awesome-mdbook) 
* [PropTesting](https://altsysrq.github.io/proptest-book/intro.html)
* [CommandLineApplications#testing](https://rust-lang-nursery.github.io/cli-wg/tutorial/testing.html)
* [Fuzzing Book](https://rust-fuzz.github.io/book/)
   
## Crates

Turns out, there is an entire subcategory on crates.io [Development tools::Testing](https://crates.io/categories/development-tools::testing)

### Mocking
* [MockAll](https://crates.io/crates/mockall) ([Examples](https://crates.io/crates/mockall_examples), [Derive Macro](https://crates.io/crates/mockall_derive))
* [Mocktopus](https://crates.io/crates/mocktopus)
* [mock_derive](https://crates.io/crates/mock_derive)
* [mockers](https://crates.io/crates/mockers)
* [simulacrum](https://crates.io/crates/simulacrum)
* [Mockiato](https://crates.io/crates/mockiato)
* [mockito](https://docs.rs/mockito/0.21.0/mockito/)(http mocks)

### Snapshop Testing

* [Insta](https://crates.io/crates/insta) + [cargo-insta](https://crates.io/crates/cargo-insta)

### Matchers

* [matches](https://crates.io/crates/matches)
* [assert matches](https://crates.io/crates/assert_matches)
* [fuzzy matcher](https://crates.io/crates/fuzzy-matcher)
* [try_match](https://crates.io/crates/try_match)

### Generated output matchers

* [specker](https://crates.io/crates/specker) A framework to collect test inputs and expected outputs from multiple files and check them. Used to test code generation (last update 2017, *needs way more examples*)

### [Diffing](https://crates.io/keywords/diff)
* [prettydiff](https://crates.io/crates/prettydiff)
* [differ](https://crates.io/crates/differ)

### [Assertions](https://crates.io/keywords/assert)
* [assert](https://crates.io/crates/assert)
* [galvanic-assert](https://crates.io/crates/galvanic-assert)
* [difference](https://crates.io/crates/difference)
* [pretty_assertions](https://crates.io/crates/pretty_assertions)
* [static assertions](https://crates.io/crates/static_assertions)
* [spectral](https://crates.io/crates/spectral)
* [assert_fs](https://crates.io/crates/assert_fs)

### FFI Testing
* [ctest](https://crates.io/crates/ctest)

### Coverage

* [tarpaulin](https://github.com/xd009642/tarpaulin)
* [cargo-kcov](https://crates.io/crates/cargo-kcov)
* [grcov](https://crates.io/crates/grcov)


### Fuzzing
* see the book section
* [afl.rs](https://github.com/rust-fuzz/afl.rs)
* [cargo-fuzz](https://crates.io/crates/cargo-fuzz)
* [honggfuzz](https://crates.io/crates/honggfuzz)

### Property Testing
* https://crates.io/crates/quickcheck https://crates.io/crates/quickcheck_macros

* https://crates.io/crates/proptest https://crates.io/crates/proptest-derive

### Parameterized Testing
* [test-case](https://crates.io/crates/test-case)

### Mutation Testing

* [mutagem](https://crates.io/crates/mutagen)

### Harnesses/Frameworks

* [rspec](https://crates.io/crates/rspec)  [![Build Status](https://travis-ci.org/rust-rspec/rspec.svg?branch=master)](https://travis-ci.org/rust-rspec/rspec) [![Coverage Status](https://coveralls.io/repos/github/rust-rspec/rspec/badge.svg)](https://coveralls.io/github/rust-rspec/rspec) [![Crates.io](https://img.shields.io/crates/v/rspec.svg?maxAge=2592000)](https://crates.io/crates/rspec) [![Crates.io](https://img.shields.io/crates/l/rspec.svg?maxAge=2592000)](https://github.com/rust-rspec/rspec/blob/master/LICENSE)
* [speculate](https://crates.io/crates/speculate) [![Build Status](https://travis-ci.org/utkarshkukreti/speculate.rs.svg?branch=master)](https://travis-ci.org/utkarshkukreti/speculate.rs) [![speculate at crates.io](https://img.shields.io/crates/v/speculate.svg)](https://crates.io/crates/speculate)
* [Shiny](https://github.com/farcaller/shiny) (last commit 2016)
* [rstest](https://github.com/la10736/rstest) *a Fixture based Testing Framwork*

### Test Generation

* [test-generator](https://crates.io/crates/test-generator) creates tests based on files

### Model Based Testing

* [model](https://crates.io/crates/model)

### Testing Webservices

* https://crates.io/crates/drill


### More Cargo Tools
* Testing feature combinations: [cargo featomatic](https://github.com/Nemo157/cargo-featomatic) (incomplete, help welcome)
* "Testing" licenses [https://github.com/Nemo157/cargo-lichking](https://github.com/Nemo157/cargo-lichking)
* Look for possible security vulnerabilities: https://github.com/RustSec/cargo-audit

### Testing Documentation
* https://crates.io/crates/skeptic
* https://crates.io/crates/docmatic

### Testing CommandLine Applications
* https://crates.io/crates/assert_cmd
* [assert_cli](https://crates.io/crates/assert_cli): the sucessor is [assert_cmd](https://crates.io/crates/assert_cmd)

## CI

* [crate-ci book](https://crate-ci.github.io/) contains general suggestions on maintaining high crate quality
* [Azure Pipelines](https://crate-ci.github.io/azure-pipelines/) contains great templates for cross-platform testing

## BlogPosts
* [How Rust is Tested](https://brson.github.io/2017/07/10/how-rust-is-tested)
* **[Mocking libraries comparison](https://asomers.github.io/mock_shootout/)**
* [On Mocking Rust](https://tech.labs.oliverwyman.com/blog/2018/05/21/on-mocking-rust/)
* [Mocking in Rust with conditional compilation](https://klau.si/blog/mocking-in-rust-with-conditional-compilation/)
* [How to Mock Time in Rust Tests and Cargo Gotchas We Met](https://blog.iany.me/2019/03/how-to-mock-time-in-rust-tests-and-cargo-gotchas-we-met/)
* [Kcov and tarpaulin code coverage](https://blog.knoldus.com/bid-adieu-to-tarpaulin-html-reports-are-here-for-rust/)
* [Tutorial: How to collect test coverages for Rust project](https://users.rust-lang.org/t/tutorial-how-to-collect-test-coverages-for-rust-project/650/14)
* [Rust Code Coverage Guide: kcov + Travis CI + Codecov / Coveralls](https://sunjay.dev/2016/07/25/rust-code-coverage)
* [Performance Testing on Travis CI](https://beachape.com/blog/2016/11/02/rust-performance-testing-on-travis-ci/)
* [Coverage with kcov + Travis CI + Codecov / Coveralls](https://sunjay.dev/2016/07/25/rust-code-coverage)
* [Testing a Rust Command Line Tool](https://mattgathu.github.io/testing-rust-cli-apps/)(for [assert_cli](https://crates.io/crates/assert_cli))
* [Rust Mutation Testing](https://llogiq.github.io/2016/03/24/mutest.html)(for [mutagem](https://crates.io/crates/mutagen))
* [Testing With Unused Arguments](https://llogiq.github.io/2015/08/17/test.html)

## Talks
* [Testing strategies and pattern for efficient TDD in Rust by Thomas Wickham](https://www.youtube.com/watch?v=U3F7uAOCjEo)

## Patterns

## Other Awesomes

* [zonyitoo awesome#testing](https://github.com/zonyitoo/awesome-rust#testing)
* [rust-unofficial awesome#testing](https://github.com/rust-unofficial/awesome-rust#testing)
* [for completenes, this one has no testing section](https://github.com/queenypingcap/awesome-rust)
* [rust learning:ci/testing](https://github.com/ctjhoa/rust-learning#ci--testing)
* [eRFC 2318: custom tests frameworks](https://github.com/rust-lang/rust/issues/50297)
