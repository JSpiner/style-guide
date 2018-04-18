# RIDI Style Guide

### Language

- [HTML](HTML.md) - HTML, Twig/Jinja2 코딩 스타일
- [JavaScript](JavaScript)
- [Less](Less.md) - Less/CSS 코딩 스타일
- [MariaDB(MySQL)](MariaDB(MySQL).md) - DDL, DML 작성 규칙
- [PHP](PHP)
- [Python3](Python)


### Platform

- [Android](Android.md) - Kotlin, Java, XML 코딩 스타일
- [iOS](iOS.md) - [Swift](Swift), Objective-C 코딩 스타일
- [Qt](Qt.md) - C++, XML 코딩 스타일
- [CMS 개발 가이드](CMS.md) - 내부 시스템 개발 가이드


### Communication

- [슬랙 사용 규칙](Slack.md)
- [HTTP API 작성 규칙](API.md)
- [UI 텍스트 작성 가이드](UI/Text.md)


<br>

## 규칙을 정하는 규칙

우리의 기조는 아래와 같다. (중요한 순서대로)

1. 항목의 수를 최소화할 것
   - 반드시 지켜져야 하는 것 위주로 정할 것
   - 권장 항목은 규칙에 포함하지 말 것
2. 올바름을 추구할 것
   - 쉽지만 잘못된 것보다는 어렵더라도 올바른 쪽을 택할 것
3. 기호의 충돌이 발생했을 때에는 간결한 쪽을 택할 것
   - 간결함이 동일할 때에는 일관성이 있는 쪽을 택할 것
   - 일관성이 동일할 때에는 대중성이 있는 쪽을 택할 것
4. 코드의 작성자보다 리뷰어의 입장을 우선할 것
   - 불필요한 diff를 최소화 할 것
5. 개발도구 중립성을 지킬 것
   - 중립성의 범위는 이해관계자로 한정할 것


<br>

## 코드 리뷰 원칙

1. 타협하지 않습니다.
   - 충분히 좋아야 올바르게 리뷰한 것입니다.
2. 의견보다 사실을 주장합니다.
   - 사실에는 출처가 따라야 하고, 의견에는 이유가 따라야 합니다.
3. 프리뷰가 필요하지 않은지를 먼저 고민합니다.
   - 구현(WHAT)보다 중요한 것은 설계(HOW)입니다.
   - 설계를 논의해야 하는 시기는 리뷰 단계가 아닌 프리뷰 단계입니다.
4. 리뷰 수단을 리뷰 도구에 한정하지 않습니다.
   - 리뷰는 커뮤니케이션이며 댓글은 이를 위한 최고의 수단이 아닙니다.
   - 가능한 모든 수단을 사용하여 토론하되 결론은 반드시 기록해야 합니다.
5. 상대방의 시간이 낭비되지 않도록 배려해야 합니다.
   - 요청자는 코드의 작성 배경, 의도된 동작, 테스트 방법 등을 충분히 설명해야 합니다.
   - 온전한 리뷰가 늦어지는 것보다는 늦어지지 않는 부분적인 리뷰가 더 좋습니다.
