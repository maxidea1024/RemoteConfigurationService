# Remote Configuration Service

## Remote Configuration Service

.NET Core 환경에서 실행되는 분산 configuration 서비스입니다.
.json, .yaml, .ini 파일 형식을 지원합니다.

스토리지는 git, file system을 지원합니다.

redis pub/sub 기능을 이용해서 변경된 configuration 파일들을 즉각적으로 반영할 수 있습니다.

## 특징

- 원격 서버에 있는 configuration 파일들을 RESTful HTTP API를 통해서 가져옵니다.
- .NET 프레임워크에 이질감 없이 손쉽게 통합될 수 있습니다.
- 클라이언트 코드는 .NET에서 제공하는 ConfigurationBuilder 패턴을 준수합니다.
- 클라이언트 실시간 반영을 캡슐화합니다.
- git, 파일 시스템을 configuration storage로 사용할 수 있습니다.
- Redis의 pub/sub을 이용한 실시간 변경 감지를 할 수 있습니다.
- .json, .yaml, .ini 파일을 설정파일로 사용할 수 있습니다.
- IOptionsMonitor<T>, IOptionsSnapshot<T>를 의존성 주입으로 사용할 수 있습니다.

