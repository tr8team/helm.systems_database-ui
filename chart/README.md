# gotrade-db-ui

![Version: 1.0.0](https://img.shields.io/badge/Version-1.0.0-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: 0.0.0](https://img.shields.io/badge/AppVersion-0.0.0-informational?style=flat-square)

Install common database UIs

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| adminer.designation | string | `"adminer"` |  |
| adminer.enable | bool | `true` |  |
| adminer.image.pullPolicy | string | `"IfNotPresent"` |  |
| adminer.image.repository | string | `"adminer"` |  |
| adminer.image.tag | string | `"4.8.1"` |  |
| adminer.nodeSelector."kubernetes.io/os" | string | `"linux"` |  |
| adminer.podSecurityContext.fsGroup | int | `1000` |  |
| adminer.podSecurityContext.runAsGroup | int | `1000` |  |
| adminer.podSecurityContext.runAsNonRoot | bool | `true` |  |
| adminer.podSecurityContext.runAsUser | int | `1000` |  |
| adminer.resources.limits.cpu | int | `1` |  |
| adminer.resources.limits.memory | string | `"2Gi"` |  |
| adminer.resources.requests.cpu | string | `"100m"` |  |
| adminer.resources.requests.memory | string | `"512Mi"` |  |
| adminer.securityContext.allowPrivilegeEscalation | bool | `false` |  |
| adminer.securityContext.capabilities.drop[0] | string | `"ALL"` |  |
| adminer.securityContext.readOnlyRootFilesystem | bool | `false` |  |
| adminer.securityContext.runAsGroup | int | `1000` |  |
| adminer.securityContext.runAsNonRoot | bool | `true` |  |
| adminer.securityContext.runAsUser | int | `1000` |  |
| adminer.service.port | int | `80` |  |
| adminer.service.type | string | `"ClusterIP"` |  |
| cloudbeaver.designation | string | `"cloudbeaver"` |  |
| cloudbeaver.enable | bool | `true` |  |
| cloudbeaver.image.pullPolicy | string | `"IfNotPresent"` |  |
| cloudbeaver.image.repository | string | `"dbeaver/cloudbeaver"` |  |
| cloudbeaver.image.tag | string | `"22.3.5"` |  |
| cloudbeaver.nodeSelector."kubernetes.io/os" | string | `"linux"` |  |
| cloudbeaver.podSecurityContext.fsGroup | int | `1000` |  |
| cloudbeaver.podSecurityContext.runAsGroup | int | `1000` |  |
| cloudbeaver.podSecurityContext.runAsNonRoot | bool | `true` |  |
| cloudbeaver.podSecurityContext.runAsUser | int | `1000` |  |
| cloudbeaver.resources.limits.cpu | int | `1` |  |
| cloudbeaver.resources.limits.memory | string | `"2Gi"` |  |
| cloudbeaver.resources.requests.cpu | string | `"100m"` |  |
| cloudbeaver.resources.requests.memory | string | `"512Mi"` |  |
| cloudbeaver.securityContext.allowPrivilegeEscalation | bool | `false` |  |
| cloudbeaver.securityContext.capabilities.drop[0] | string | `"ALL"` |  |
| cloudbeaver.securityContext.readOnlyRootFilesystem | bool | `true` |  |
| cloudbeaver.securityContext.runAsGroup | int | `1000` |  |
| cloudbeaver.securityContext.runAsNonRoot | bool | `true` |  |
| cloudbeaver.securityContext.runAsUser | int | `1000` |  |
| cloudbeaver.service.port | int | `80` |  |
| cloudbeaver.service.type | string | `"ClusterIP"` |  |
| cloudbeaver.storage.class | string | `"local-path"` |  |
| cloudbeaver.storage.size | string | `"512Mi"` |  |
| commander.designation | string | `"commander"` |  |
| commander.enable | bool | `true` |  |
| commander.image.pullPolicy | string | `"IfNotPresent"` |  |
| commander.image.repository | string | `"ghcr.io/joeferner/redis-commander"` |  |
| commander.image.tag | string | `"0.8.1"` |  |
| commander.nodeSelector."kubernetes.io/os" | string | `"linux"` |  |
| commander.podSecurityContext.fsGroup | int | `1000` |  |
| commander.podSecurityContext.runAsGroup | int | `1000` |  |
| commander.podSecurityContext.runAsNonRoot | bool | `true` |  |
| commander.podSecurityContext.runAsUser | int | `1000` |  |
| commander.resources.limits.cpu | int | `1` |  |
| commander.resources.limits.memory | string | `"2Gi"` |  |
| commander.resources.requests.cpu | string | `"100m"` |  |
| commander.resources.requests.memory | string | `"512Mi"` |  |
| commander.securityContext.allowPrivilegeEscalation | bool | `false` |  |
| commander.securityContext.capabilities.drop[0] | string | `"ALL"` |  |
| commander.securityContext.readOnlyRootFilesystem | bool | `true` |  |
| commander.securityContext.runAsGroup | int | `1000` |  |
| commander.securityContext.runAsNonRoot | bool | `true` |  |
| commander.securityContext.runAsUser | int | `1000` |  |
| commander.service.port | int | `80` |  |
| commander.service.type | string | `"ClusterIP"` |  |
| labels.landscape | string | `"develop"` | L of LPSD of Gotrade Service Tree |
| labels.layer | string | `"2"` | Infrastructure layer this application belongs to |
| labels.platform | string | `"systems"` | P of LPSD of Gotrade Service Tree |
| labels.service | string | `"db-ui"` | P of LPSD of Gotrade Service Tree |
| labels.team | string | `"ESD"` | Team in charge of this chart |
| labels.version | string | `"1.0.0"` | chart version |
| pgweb.designation | string | `"pgweb"` |  |
| pgweb.enable | bool | `true` |  |
| pgweb.image.pullPolicy | string | `"IfNotPresent"` |  |
| pgweb.image.repository | string | `"ghcr.io/sosedoff/pgweb"` |  |
| pgweb.image.tag | string | `"0.14.0"` |  |
| pgweb.nodeSelector."kubernetes.io/os" | string | `"linux"` |  |
| pgweb.podSecurityContext.fsGroup | int | `1000` |  |
| pgweb.podSecurityContext.runAsGroup | int | `1000` |  |
| pgweb.podSecurityContext.runAsNonRoot | bool | `true` |  |
| pgweb.podSecurityContext.runAsUser | int | `1000` |  |
| pgweb.resources.limits.cpu | int | `1` |  |
| pgweb.resources.limits.memory | string | `"2Gi"` |  |
| pgweb.resources.requests.cpu | string | `"100m"` |  |
| pgweb.resources.requests.memory | string | `"512Mi"` |  |
| pgweb.securityContext.allowPrivilegeEscalation | bool | `false` |  |
| pgweb.securityContext.capabilities.drop[0] | string | `"ALL"` |  |
| pgweb.securityContext.readOnlyRootFilesystem | bool | `true` |  |
| pgweb.securityContext.runAsGroup | int | `1000` |  |
| pgweb.securityContext.runAsNonRoot | bool | `true` |  |
| pgweb.securityContext.runAsUser | int | `1000` |  |
| pgweb.service.port | int | `80` |  |
| pgweb.service.type | string | `"ClusterIP"` |  |

----------------------------------------------
Autogenerated from chart metadata using [helm-docs vv1.11.0](https://github.com/norwoodj/helm-docs/releases/vv1.11.0)
