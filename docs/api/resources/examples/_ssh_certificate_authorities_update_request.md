
#### Example Request
```bash
curl \
-XPATCH \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"metadata":"{\"region\": \"us-east-1\"}"}' \
https://api.ngrok.com/ssh_certificate_authorities/sshca_2GjEzVdt5yPlM1uBLTZ7XZPAvdC
