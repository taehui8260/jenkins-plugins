# jenkins-plugins

Jenkins 설치 후, 빌드 및 배포 작업을 자동화하고, 다양한 SCM과 통합을 원활하게 진행하기 위해 필요한 플러그인들입니다.

## 1. 기본 플러그인 목록

- **Folders**: 프로젝트를 폴더로 분류하여 관리할 수 있도록 해주는 플러그인입니다.
- **OWASP Markup Formatter**: OWASP 기준에 따라 안전한 마크업 포맷을 지원하여 보안을 강화합니다.
- **Build Timeout**: 빌드 시간이 특정 시간을 초과하면 빌드를 자동으로 중단시킵니다.
- **Credentials Binding**: 자격 증명(암호, 토큰 등)을 안전하게 사용하기 위한 플러그인입니다.
- **Timestamper**: 빌드 로그에 타임스탬프를 추가해 로그 분석을 용이하게 합니다.
- **Workspace Cleanup**: 빌드 작업 전후에 워크스페이스를 정리하여 불필요한 파일을 제거합니다.
- **Ant**: Apache Ant 빌드 도구를 지원하는 플러그인입니다.
- **Gradle**: Gradle 빌드 도구를 지원하는 플러그인입니다.
- **Pipeline**: 파이프라인 스크립트를 통해 Jenkins 작업을 자동화하는 필수 플러그인입니다.
- **GitHub Branch Source**: GitHub의 특정 브랜치를 소스로 사용하여 빌드를 자동화할 수 있습니다.
- **Pipeline: GitHub Groovy Libraries**: 파이프라인에서 GitHub의 Groovy 라이브러리를 사용할 수 있게 해줍니다.
- **Pipeline Graph View**: 파이프라인 빌드의 그래프를 시각적으로 보여줍니다.
- **Git**: Git을 통한 소스 코드 관리를 지원하는 필수 플러그인입니다.
- **SSH Build Agents**: SSH를 사용하여 원격 빌드 에이전트와 통신하는 데 필요한 플러그인입니다.
- **Matrix Authorization Strategy**: 권한 관리를 매트릭스 형식으로 설정할 수 있게 해줍니다.
- **PAM Authentication**: PAM 인증을 통해 시스템 계정 인증을 Jenkins에서 사용할 수 있게 해줍니다.
- **LDAP**: LDAP를 통한 사용자 인증을 지원합니다.
- **Email Extension**: 빌드 성공, 실패 등의 상황에 대해 이메일 알림을 확장하여 전송할 수 있습니다.
- **Mailer**: 기본 메일 발송 플러그인으로, 빌드 결과를 이메일로 통지할 수 있습니다.
- **Dark Theme**: Jenkins 인터페이스에 다크 테마를 적용하여 시각적 편안함을 제공합니다.
- **Slack Notification**: 빌드 결과를 Slack으로 알림을 보내기 위한 플러그인입니다.

