# rpcenum

Es una herramienta modificada de la original realizada por Aka s4vitar, la herramienta original solamente permite realizar enumeración de DA a través de RPC con una Null Session (sin proporcionar credenciales).

Esta es la nueva variante de la herramienta que permite realizar el mismo proceso pero disponiendo de credenciales válidas del dominio.

# Ejemplo de uso:

❯ rpcenum -e All -i 10.10.10.10 -u 'user' -p 'password'

[-] Uso: rpcenum

	e) Enumeration Mode
		DUsers (Domain Users)
		DUsersInfo (Domain Users with info)
		DAUsers (Domain Admin Users)
		DGroups (Domain Groups)
		All (All Modes)

	i) Host IP Address
	u) Username
	p) Password
	h) Show this help panel
