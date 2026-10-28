SUNGBIN BYUN 포트폴리오 — 쉬운 관리 버전

이 폴더는 영화 스틸을 크게 보여주는 홈페이지와, 브라우저에서 작품 정보를 수정할 수 있게 하는 Pages CMS 설정을 포함합니다.

중요: 사이트를 공개하는 과정에서 처음 한 번은 GitHub 저장소를 만들고 파일을 업로드해야 합니다. 그 다음부터는 Pages CMS에서 글과 사진을 관리할 수 있습니다.

1) GitHub 계정이 없다면 https://github.com/signup 에서 가입합니다.
2) https://github.com/new 에서 Public 저장소를 새로 만듭니다. 저장소 이름은 예: sungbinbyun-portfolio 로 지정해도 됩니다.
3) 이 압축파일의 안에 있는 모든 파일과 폴더를 저장소 루트에 업로드합니다. .pages.yml 파일도 꼭 포함해야 합니다.
4) GitHub 저장소 Settings > Pages > Build and deployment 에서 Deploy from a branch, branch main, folder /(root)를 선택하고 Save 합니다.
5) 공개 사이트 주소는 https://사용자이름.github.io/저장소이름/ 형태가 됩니다. 게시에는 몇 분이 걸릴 수 있습니다.
6) https://app.pagescms.org 에 접속해 GitHub로 로그인하고, 이 저장소에 대한 Pages CMS 앱 접근 권한을 허용합니다. 저장소를 열면 홈페이지 글과 Films 목록을 시각적으로 수정할 수 있습니다.
7) 이미지/작품 수정은 Pages CMS의 Site settings(Homepage text and hero)와 Films에서 합니다. 업로드 이미지는 images/uploads 폴더에 저장됩니다. 저장한 변경사항은 GitHub에 반영되고 Pages 사이트가 다시 게시됩니다.

처음 사이트를 만들 때 필요한 기술 설정은 위 순서로 한 번만 진행하면 됩니다. Pages CMS는 기존 HTML을 직접 수정하지 않고 content/site.json 및 content/films.json 데이터를 수정합니다.

현재 이미지들은 디자인 참고용 Unsplash 이미지입니다. 실제 영화 스틸과 포스터로 교체하세요. 이메일 YOUR-EMAIL@example.com도 본인 이메일로 변경하세요. 영화 정보와 약력은 공개 전 반드시 검토하세요.

참고: Pages CMS 문서 https://pagescms.org/docs/quick-start/
GitHub Pages 안내 https://docs.github.com/en/pages/getting-started-with-github-pages
