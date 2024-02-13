
> 참고 URL: https://gist.github.com/JARVIS-AI/a20f38c88bee6b0d2fd5938b94bac438

## Key 생성하기
###### RSA
`ssh-keygen -t rsa -b 4096 -C "Your EMAIL"`
###### ED25519
`ssh-keygen -t ed25519 -C "Your EMAIL"`

키 생성 경로
-  RSA
	`~/.ssh/id_rsa`
	`~/.ssh/id_rsa.pub`
- ED25519
	`~/.ssh/id_ed25519`
	`~/.ssh/id_ed25519.pub`

