# Eaten Muffin

삽질, 그 예술에 관하여..

## 글쓴이 등록

`_data/authors.yml`의 `Billy Rick`을 참고해서 글쓴이 프로필을 등록할 수 있어요.

## 글 작성

`_posts/2020-06-22-first-post.md` 파일을 그대로 복사한 뒤, 수정하고 커밋하면 끝이에요!

## 로컬 환경에서 미리보기

`master` 브랜치에서 직접 작업하는 것도 가능하지만, `authors/{글쓴이}` 브랜치를 사용해서 부담 없이 작업할 수 있어요.

이 경우는 결과물을 원격에서 볼 수 없기 때문에 미리 보려면 로컬에서 직접 빌드해야 해요. 

1. 아래의 두 가지가 필요해요.

    - [jekyll](https://jekyllrb.com/docs/installation/)
    - [bundler](https://bundler.io/)

2. 각각의 링크를 클릭하면 플랫폼에 맞는 설치 방법을 확인할 수 있어요.
   
    `jekyll`, `bundler`가 모두 준비되었으면, `bundle install`으로 필요한 것을 설치해요.

    ```bash
    $ bundle install
    > Bundle complete! X Gemfile dependencies, XX gems now installed.
    > Use `bundle info [gemname]` to see where a bundled gem is installed.
    ```

3. 로컬에서 미리보기를 할 수 있어요.

    ```bash
    $ bundle exec jekyll serve
    > ...
    > Server address: http://127.0.0.1:4000/
    > Server running... press ctrl-c to stop.
    ```

    위 상태에서 브라우저 주소 창에 `http://127.0.0.1:4000/`을 입력하면 미리 볼 수 있어요!
