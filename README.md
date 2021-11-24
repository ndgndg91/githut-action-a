# githut-action-a

github-action-a repository 에서 v[0-9].[0-9].[0-9] 형식의 tag push 시 workflow 가 실행되어 마지막에 github-action-b 레포지토리의 github action workflow 을 작동시킨다.

Create a repository dispatch event API 를 통해서 github-action-b repository 를 호출한다.
https://docs.github.com/en/rest/reference/repos#create-a-repository-dispatch-event

https://github.com/ndgndg91/githut-action-b
