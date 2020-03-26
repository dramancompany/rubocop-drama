# Rubocop 설치
- Gemfile 내에 rubocop, rubocop-rails 가 포함되어 있어야 한다

## Rubocop 버전
- rubocop 0.80.1 이상
- rubocop-rails 2.5.0 이상

# Rubocop Rule 설정 방법
- 프로젝트 루트에 `.rubocop.yml` 파일을 생성한다.
- 아래와 같이 내용을 입력한다. Ruby 버전과 Rails 버전은 프로젝트에 맞게 설정한다

```yaml
inherit_from:
  - https://raw.githubusercontent.com/dramancompany/rubocop-drama/master/.rubocop_drama.yml

AllCops:
  TargetRubyVersion: 2.6.3
  TargetRailsVersion: 5.2.3
```
