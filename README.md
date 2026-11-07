# Skaffelista-agent

UCP-profil (Universal Commerce Protocol) for en privat prisvakt.

Agenten gjør bare katalogoppslag (pris og lagerstatus) på produkter eieren følger, høyst én gang i
døgnet per produkt. Den bruker ikke handlekurv, kasse eller ordre.

Profilen ligger på `/.well-known/ucp` og inneholder den offentlige nøkkelen som kallene signeres med
(RFC 9421, Web Bot Auth-form, ES256). User-Agent: `Skaffelista-prisvakt/1.0`.
