# Coralina Jewelry Co.

> caribbean roots × gulf coast — handmade with coastal magic

## Local development

```sh
gleam run     # run main
gleam test    # run tests
gleam format  # format src/ and test/
```

Requires Gleam ≥ 1.16 and Erlang/OTP ≥ 27.

## How it ships

`ci.yml` runs format/build/test on PRs and on pushes to `main`. Vercel watches `main` and auto-deploys `public/`.
