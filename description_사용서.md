# Note.
한 번의 트리거(push)가 발생하면, github-actions이 실행되면서 output files가 생성된다.
따라서 github-actions이 실행되었을 때에는 반드시 git pull을 실행하고 코드를 수정해야 한다.

## overview를 clone/fork 하여 자신의 레포지토리에서 사용 가능하도록 custom 하는 방법
1. 레포지토리의 이름은 자신의 github name과 동일하게 생성한다. (junius06/junius06)

2. template.svc 에서 코드를 수정한다.