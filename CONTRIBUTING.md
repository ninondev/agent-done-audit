# Contributing

Issues are read by the maintainer. Pull requests are welcome.

Use Python 3.9 or later. The scripts and tests use only the standard library.

```sh
nice -n 10 python3 -m unittest -v
```

If you change the fixture, edit `tests/build_fixture.py` and run it again with
`python3 -I tests/build_fixture.py`. Use synthetic data only. Do not put your
transcripts, private paths or message text in an issue or pull request. If you
share results from your own transcripts, share the aggregate tables the scripts
print.

The scripts, text and tables are under the MIT License. See [LICENSE](LICENSE).
