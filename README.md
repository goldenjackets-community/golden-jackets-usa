# 🏆 Golden Jackets USA

Community website celebrating North American professionals who earned all active AWS certifications.

🔗 **[goldenjacketsus.com](https://goldenjacketsus.com)**

## Chapter Lead
- **Dr. Justin Cook** — Global AWS CTO of the AWS Alliance at Atos

## Members
- Dr. Justin Cook (Chapter Lead)
- Noor Sabahi (Founding Member)
- Jenn Bergstrom (Founding Member)

## AWS Services
| Service | Purpose |
|---------|---------|
| **S3** | Static website hosting |
| **CloudFront** | CDN, SSL termination |
| **Route 53** | DNS management |
| **Cognito** | User authentication (Members Lounge) |
| **API Gateway** | HTTP API |
| **Lambda** | Backend logic (apply, admin, counter) |
| **DynamoDB** | Visitor counter |
| **GitHub Actions** | CI/CD pipeline |

## Deploy
Push to `master` → GitHub Actions → S3 sync → CloudFront invalidation
