StartUp 소프트웨어 개발 조직이 갖추어야 할 문화
======================
개발 전반에 걸친 가이드 문서화
---------------
이 문서들은 개발에 필요한 최소한의 이해를 돕고자 하는 것이지 개발에 전부라고 생각하지 않으며, 수동적 추종자가 아닌 창의적 능동자가 되길 빌며, 다양한 케이스들을 탐구해서 해당 문서를 개선해주고, 필요한 문서들이 있다면 자유롭게 추가해 주세요.

- 개발 환경 가이드 : 좋은 개발 도구와 더불어 신규 프로젝트, 신규 입사자에게 필요한 설정 정보들, 필요한 어플, 그리고 그 어플들의 사용 방법, 단축키 등 개발 환경에 필요한 가이드를 제공해 불필요한 비용을 줄인다.
 - [Mac에서 개발환경 구축 가이드][dev_guide]
 - [Mac에서 git 환경](https://github.com/mimul/dev-environment/blob/master/mac-git.md)
- [개발 프로세스 가이드](https://github.com/mimul/dev-environment/blob/master/dev-process.md): 최신 트렌드를 반영한 최소한의 개발 프로세스에 대한 가이드를 제공한다.(Trello + Github + Slack)
- [코드 리뷰](https://github.com/mimul/dev-environment/blob/master/code-review.md) : 코드 리뷰에 필요한 정보들을 정리해 제공한다.
- 코드 개선
 - [정적 분석](https://github.com/mimul/dev-environment/blob/master/static-analysis.md)
 - 리팩토링 가이드(Comming soon) : 좋은 코드를 작성하기 위한 몇가지 지침을 제공한다.
- [Markdown Template](https://github.com/mimul/dev-environment/blob/master/markdown-template.md) : 필요한 Markdown 문법 등 사용 가이드 제공해 활용도를 높여준다.
- 기술 블로그(Comming soon)

코드 리뷰 장려
---------------
좋은 코드란 다른 사람이 읽기 쉬운 코드가 좋은 코드라 한다. 그럼 좋은 코드를 작성하는 게 왜 중요한가는 구현패턴에서 Kent Beck이 두 가지 이유를 들었다.

> 첫째는 경제적인 효과를 위해. 다른 사람도 쉽게 읽을 수 있는 코드를 쓴다면 코드의 분석에 걸리는 시간을 줄여 개발 비용이 줄어든다는 것.
> 둘째는 인간적 내부 효과(동기요인)를 위해. 개발자는 코드를 작성하는 것 자체가 기쁨이고, 스스로 자부심도 가질 수 있고, 커뮤니티의 일원으로서 인정 받을 수도 있고, 내 코드를 다른 사람이 이해하고 평가하고 사용하고 확장하면 더 기쁨이다. 그리고 엔지니어가 돈을 받는 데에 대한 좋은 보답 중에 하나가 좋은 코드를 작성하는 것이다.

좋은 코드를 작성하는 데 도움을 가장 많이 받을 수 있는 방법이 바로 코드 리뷰라고 생각한다. 이는 대화를 통해 내가 생각지 못한 남의 철학이나 좋은 코드를 볼 수 있고 남에게 보여야 하는 심리적 중압감이 있어 잘 짜려고 노력하게 한다.

그럼 좋은 코드 리뷰를 하려면 어떻게 해야 하나?
- 코드 리뷰는 매우 좋은 일이지만, 잘 일어나지 않을 가능성이 커서 정말 좋은 인상을 심어줘야 한다. 이건 정말 대의 명제다.
- 마음을 열고 다른 사람이 자신의 의견을 잘 말할 수 있도록 해주고 경청하는 자세가 아름답다. 말을 안 해도 서로가 배울 수 있다.
- 세세한 버그를 볼 것이 아니라, 전체 구성과 흐름에 문제가 없는지 주목하자. 불필요한 오버 엔지니어링은 없는지도.
- 토론한다는 자체만으로도 조직에는 큰 도움이 된다. 개발 문화의 단초가 된다.
- 학습은 조롱하는 것이 아니라 같이 맞대어 동료애를 확인하는 것이다.
- 자신보다 열등하다고 생각하는 사람에게서도 배울 것은 무한하다. 단정 짓지 말자.
- 코드 리뷰에 참여하는 사람들 모두가 내가 대상자라는 생각으로 내가 이렇게 코딩했을 때 어떻게 할 것인가를 생각하고 그 입장에서 말하는 버릇을 가지자. 그러면 비판적 자세는 나올 수 없다.
- 토론을 자주 하며, 논쟁 할 때는 대상자가 불특정 다수가 되는 환경이 만들어졌을 때 시작하자.

그 외 좋은 코드 작성하려면 어떻게 해야 하나?
- 네이밍(Comming soon)
- 디자인 패턴 활용
- 리팩토링 가이드(Comming soon)

공유
---------------
내가 적용한, 공부한 기술이나 다양한 학습 내용을 동료들에게 공유하고 관심이 가는 기술들에 대해서는 학습활동을 장려하도록 한다. 소프트웨어 개발 조직은 장기적으로 본인이 자립하고 성장하는 것을 촉진하기 위해서도 전체 조직이 지속해서 학습하는 습관을 지닐 필요가 있다. 협력사, 외부의 사람들도 같이해서 다양한 사람들이 참여하고 함께 배우고 경험을 공유하면서 빠른 성장을 촉진하고 더불어 나를 알릴 수 있는 기회도 된다. 

또한, 관리자도 학습에 참여해야만 중대한 의사결정이 많은 계층이다 보니 시행착오를 줄일 수 있고, 의사결정의 비용(커뮤니케이션 등)을 줄여주며, 학습은 개인의 문제가 아닌 조직에서 접근해야 하는 필요성도 알 수 있다.

알고 있는 것을 남에게 공유하는 것이 좋은 진짜 이유는 모르는 사람은 정보를 얻고, 공유한 사람은 실수를 하지 않기 위해 더 정확성을 추구하게 되고 피드백을 통해 배우게 되어 참여자, 공유자 모두 좋은 결과를 가져오는 것이 바로 공유하는 즐거움이다.

또한, 장애나 소스 상의 오류, 비효율적인 것, 코드 리뷰 등에 대해서는 개발자가 공유하는 걸 부끄러워하지 않게 하는 환경을 만들어야 오류 숨김 현상을 억제할 수 있다.

프로세스 중심이 아닌 능력 중심
---------------
테크가 중요한 시대는 프로세스보다는 능력이 중심인 시대가 되어버렸다. 올바른 프로세스를 사용하는 것보다 높은 기술력 즉, 능력을 갖추는 것이 더 중요하다. 프로세스와 도구, 환경을 잘 사용하면 조직에 동화되어 일을 잘하는 것처럼 보일 순 있으나, 기술력이 뒷받침 되지 않는다면 좋은 프로그램을 보장해 주지도, 나쁜 프로그래머를 구제해 주지는 않는다.

기업은 도구룰 갖춰주는 것뿐만 아니라, 직원 스킬의 낮음을 보완해 줄 것이 무엇인지도 고민해 봐야 한다.

기다림(Slow)
---------------
> Writing software is an art, and it takes About Ten years to Really Get good at it.
> 소프트웨어를 개발하는 것은 예술이고 정말 좋은 제품을 얻기 위해서는 10년이 걸린다.
> Richard Gabriel - "The Poetry of Programming"

소프트웨어 엔지니어가 제 몫을 하려면 정말 10년이 걸릴 수 있다. 능력이 없다고 말하기 전에 정말 장기적으로 한 사람에게 기업이 얼마나 많은 노력을 했는지 먼저 생각해 볼 필요가 있다.

그리고 매우 급한 일정에 놓여있고 빨리 개발하는 개발자를 편애하는 환경 속에서 있다 보니 생산성이 암묵적으로 중요하다는 생각이 우리의 머리에 자리를 잡고 있다. 그 부작용으로 창의력과 문제 해결 능력을 갖추고자 생각의 시간을 갖는 사람을 프로젝트에서 방해자로 간주하기 쉽게 되고 사람을 단지 목적을 달성하기 위한 종속자 역할만을 바라보게 된다.

그래서 단순 개발 효율화를, 빠른 피처 개발만이 생산성으로 치부해 버리고 생산성과 창의성의 반비례가 고착화된다.

기다림의 철학으로 구성원과 조직의 비전을 이해하고, 부족한 부분을 찾거나 메워주고, 상호 인식의 전환과 공유 노력을 하고, 목표에 기반을 조직력 증대 등을 모든 이들이 같이 노력하는 환경을 만들어야 한다.

자기 주도
---------------
작은 기업은 실행력이 빨라야 살아 남는다. 그럴려면 의사결정이 빨라야하고 또 그러기 위해서는 관리자가 필요하지 않는 조직이 되어야 한다. 그래서 결국, 스스로가 완결형 인간이 되어야 한다. 일을 스스로 진행하고 일이 완료되면 다음 일을 미리 찾는 등의 능동적인 모습을 가지는 것이 필요하다. 그렇지 않게 되면 어느 누구는 일을 시켜야하고 일을 시키면 완료됨을 확인해야하니 관리가 들어가게 되고 의사결정 과정은 느려지게 되며, 문화의 태동보다 사내 정치가 자리잡게 된다.

그러나, 자기마음대로 생각하고 마음대로 이행하는 것도 문제가 될 수 있다. 그래서 우리에게 필요한 건 스스로 생각한 것을 확신하는 것이 아니라, 남에게 확인하거나 제안을 하면서 팀과 회사의 목표를 가지고 토론하면서 다음의 일들을 결정하고 그렇게 진행하면 된다. 듣기보다 의견내기가 더욱 중요한 이유이다. 코딩도 마찬가지다.

더불어, 문화의 혜택을 자신의 편이로 활용하기보다는 더 나은 문화를 만드는 데 일조하도록 지속해서 노력해야 그 문화가 유지된다.

자율
---------------
업무, 시간, 기술, 팀에 자율성을 부여하자. 프로세스, 관리 등은 업무의 성과를 저해하는 중요한 요인들이다. 자율성에서부터 문화란 게 생기기 시작한다고 믿고 있다.

관련 참조 정보들
---------------
1. [작은 조직에서 엔지니어 문화 만들기법](http://www.mimul.com/pebble/default/2011/07/23/1311414084290.html)
2. [작지만 강한 팀 꾸리기](http://www.mimul.com/pebble/default/2011/01/31/1296401014320.html)
3. [조직의 생산성을 올리려면](http://www.mimul.com/pebble/default/2015/04/30/1430380681414.html)

[dev_guide]: https://github.com/mimul/dev-environment/blob/master/mac-dev-env.md
