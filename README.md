# blog_ksk

AI / 데이터 학습 기록용 GitHub 블로그입니다. Jekyll + [minimal-mistakes](https://github.com/mmistakes/minimal-mistakes) 테마로 만들어졌고, GitHub Pages에서 자동으로 빌드됩니다.

- 사이트 주소: https://segwonkim.github.io/blog_ksk/
- 새 글 작성: `_posts/YYYY-MM-DD-제목.md` 형식으로 파일을 추가하면 됩니다.
- 로컬 미리보기 (Ruby/Bundler 설치 필요):

```bash
bundle install
bundle exec jekyll serve
```

- 아직 날짜가 안 된(미공개) 글까지 미리보기 (관리자 전용, 로컬에서만 보임):

```bash
bundle exec jekyll serve --future
```

  `_config.yml`에는 `future: true`를 넣지 않았습니다. 그래야 실제 배포되는 사이트(GitHub Pages)는 예약된 날짜가 되기 전까지 글을 숨기고, `--future` 플래그를 준 로컬 서버에서만 관리자가 미리 확인할 수 있습니다.
