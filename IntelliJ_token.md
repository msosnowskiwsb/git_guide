# Autoryzacja za pomocą tokenu IntelliJ - GitHub

Żeby wygenerować token w GitHub należy po kliknięciu na ikonę swojego konta wybrać opcję `Settings`. Następnie przejść do sekcji `Developer Settings`, a następnie `Personal access tokens`. W tym miejscu należy kliknąć `Generate new token`.

W formularzu należy podać opis i wybrać 2 wartości: `repo` oraz `gist`:

![Token 1](static/IntelliJ_token/token1.png)
![Token 2](static/IntelliJ_token/token2.png)

Po potwierdzeniu widać wygenerowany token (zielone pole):

![Wygenerowany token](static/IntelliJ_token/token_to_copy.png)

Token po wygenerowaniu trzeba skopiować, bo po przejściu na inną stronę już nie będzie widoczny.

Jeżeli mamy wygenerowany token należy w `IntelliJ` z górnego menu wybrać: `File` --> `Settings` --> `Version Control` --> `GitHub`.

Należy kliknąć znak `+` oraz `Use token`:

![Droga do podania tokenu w IntelliJ](static/IntelliJ_token/github_route_to_token_formula.png)

W widocznym oknie należy wprowadzić wygenerowany wcześniej token:

![Dodanie tokenu w IntelliJ](static/IntelliJ_token/add_token_to_intellij.png)

Po dodaniu powinien być widoczny wpis:

![Widoczna pozycja z kontem github](static/IntelliJ_token/after_adding_token_in_intellij.png)
