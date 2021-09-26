# Wrzucenie projektu IntelliJ do repozytorium GIT

W tym pliku znajdziesz informację jak utworzyć nowy projekt Java w IntelliJ oraz wrzucić go na repozytorium zdalnego GitHub.

## Stworzenie nowego projektu Java

Po uruchomieniu IntelliJ wybieramy opcję `Create New Project':

![Okno startowe IntelliJ](static/IntelliJ_project/start_window_intelliJ.png)

Wybieramy odpowiednią wersję SDK:

![SDK](static/IntelliJ_project/new_project_formula_1.png)

Wybieramy opcję `Create project from template`:

![Template command line](static/IntelliJ_project/new_project_formula_2.png)

Podajemy nazwę projektu:

![Nazwa projektu, paczki](static/IntelliJ_project/new_project_formula_3.png)

Po stworzeniu będzie projekt Java z już utworzoną klasą `Main`:

![Projekt w IntelliJ](static/IntelliJ_project/project_in_intellij.png)

Zatem został założony nowy projekt Java w IntelliJ.

Żeby wrzucić projekt Java znajdujący się w IntelliJ do na GitHub wystarczy, że skorzystamy z menu IntelliJ. W górnym menu wybieramy `VCS` --> `Import into Version Control` --> `Share Project on GitHub...`. Po kliknięciu pojawi się okno, w którym od razu będziemy mieli nazwę repozytorium, wskazaną domyślną nazwę repozytorium zdalnego jako origin oraz pole do wpisania opisu dla repozytorium:

![Share project on GitHub](static/IntelliJ_project/share_project_on_hithub.png)

Po kliknięciu `Share` mamy okno z możliwością dodania pierwszego commit. Wybieramy tylko plik Main.java:

![First commit](static/IntelliJ_project/first_commit.png)

Po zaakceptowaniu mamy od razu nasz projekt na GitHub:

![Screen z GitHub](static/IntelliJ_project/java_project_on_github.png)
