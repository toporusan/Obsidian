POST /api/v1/remote-auth/client HTTP/2
Host: mobile.anorbank.uz
Content-Type: application/json
Accept: application/json
Ip-Address: 94.158.63.75
Authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCIgOiAiSldUIiwia2lkIiA6ICJKS3ZLd1MzVXN5bzgtQjJLLTZFX0JjVHNaenY2dWxQd2s2QVJkMnhXSlBJIn0.eyJleHAiOjE3MjYyOTYzMzAsImlhdCI6MTcyNjIwOTkzMCwianRpIjoiOGEyM2UzMWYtNmFmOS00OGYxLWEwNzMtMTk4MThiZDJmZjdiIiwiaXNzIjoiaHR0cDovLzE5Mi4xNjguMTY3LjEvcmVhbG1zL21vYmlsZS1tYmd3IiwiYXVkIjoiYWNjb3VudCIsInN1YiI6ImY6YTEwNzY5M2YtZGFlNS00ZTI0LWIwNjUtZDVjYzU5NGE5ZTYyOjY0NzQ1NTEiLCJ0eXAiOiJCZWFyZXIiLCJhenAiOiJtb2JpbGUtbXMiLCJzZXNzaW9uX3N0YXRlIjoiMTNkNGMwMTAtNWY0Zi00ZDkxLTkwMTYtZjlkYTQwODlhYzkwIiwiYWNyIjoiMSIsImFsbG93ZWQtb3JpZ2lucyI6WyJodHRwOi8vbG9jYWxob3N0OjgwODAiXSwicmVhbG1fYWNjZXNzIjp7InJvbGVzIjpbIm9mZmxpbmVfYWNjZXNzIiwidW1hX2F1dGhvcml6YXRpb24iXX0sInJlc291cmNlX2FjY2VzcyI6eyJhY2NvdW50Ijp7InJvbGVzIjpbIm1hbmFnZS1hY2NvdW50IiwibWFuYWdlLWFjY291bnQtbGlua3MiLCJ2aWV3LXByb2ZpbGUiXX19LCJzY29wZSI6InByb2ZpbGUgZW1haWwiLCJzaWQiOiIxM2Q0YzAxMC01ZjRmLTRkOTEtOTAxNi1mOWRhNDA4OWFjOTAiLCJlbWFpbF92ZXJpZmllZCI6ZmFsc2UsImF1dGgiOiJST0xFX05PVF9DTElFTlQiLCJwcmVmZXJyZWRfdXNlcm5hbWUiOiI5OTg5MDgzMDI5ODkiLCJsYW5nIjoicnUiLCJkZXZpY2VJZCI6Ijg1MjQyNjYifQ.fkyAAYPEyZlRoc5c3qTf12kObJSaWApaZ7hSL9aaTdS-Jf3QkdaKGf3CWnImv44SYywc_GqAdRPMSUWhs-LFvLEAr9jILjm4zIeM-7LgZbNRM0dvEH2XmMj4BMOT_cLBbK5jOc6qFvfTk5PiQIHgERPMOk8MOGVyJm2Vcxx58So8c2EYCLuynTjOOS_slwi4_31m1i3XMW-wLCwGrgkZ-f2bsvYxk1KPJPHBTUQjg8lqsJNQJF13NIZ-q89Ga1YwtQUyvlYSPv4o2Y4oyfgfOpZ3Kv-4oDIENGGnCwmrSlFWFNIHkziLyig_BODSDCOjBGBzbyZ_sa4Fn3_WL25BMQ
Accept-Encoding: gzip, deflate, br
Accept-Language: ru
Platform: iOS
Deviceid: 0bdce0ddbd544c9cb6be81ef26633b77
Content-Length: 236
Ui-Version: box-2.4.0
User-Agent: iPhone, iPhone 13 Mini, iOS 17.6.1)

{"MessageContent":{"pinfl":"31706890171469","passportDateExpiration":"","passportNumber":"AD","photoHashCode":"8ba6861f-4cb8-462f-8314-7bc48c453e0f_egov","birthDay":"1989.06.17","passportSeries":"1904586","passportDateRegistration":""}}

Успешный ответ : 

HTTP/2 200 OK
Vary: Origin
Vary: Access-Control-Request-Method
Vary: Access-Control-Request-Headers
Content-Type: application/json
Content-Length: 52
Cache-Control: no-cache, no-store, max-age=0, must-revalidate
Pragma: no-cache
Expires: 0
X-Content-Type-Options: nosniff
X-Frame-Options: DENY
X-Xss-Protection: 1 ; mode=block
Referrer-Policy: no-referrer

{
"message":"Successfully send",
"success":true
}




**Ошибка :**
{
"message"``:``"hash failed verification"``,
"success"``:``false
}


