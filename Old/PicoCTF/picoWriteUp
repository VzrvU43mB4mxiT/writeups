Magikarp Ground Mission | General Skills | 30 pontos

Descrição:
Do you know how to move between directories and read files in the shell? Start the container, `ssh` to it, and then `ls` once connected to begin. Login via `ssh` as `ctf-player` with the password, `6d448c9c`
Você sabe andar por diretórios e ler os arquivos na linha de comando? Inicie a instância, conecte via ssh e dê um 'ls' para começar. Logue via ssh como 'ctf-player' com a senha '6d448c9c'

Solução:
Iniciar a instância (pelo botão na própria página)
ssh ctf-player@venus.picoctf.net -p 57545
yes
6d448c9c
ls
cat 1of3.flag.txt
	picoCTF{xxsh_
cat instructions-to-2of3.txt
	Next, go to the root of all things, more succinctly `/`
cd ..
cat 3of3.flag.txt
	5190b070}
cd ..
cat 2of3.flag.txt
	0ut_0f_\/\/4t3r_

Flag:
picoCTF{xxsh_0ut_0f_\/\/4t3r_5190b070}

-----------------------------------------------------

Lets Warm Up | General Skills | 50 pontos

Descrição:
If I told you a word started with 0x70 in hexadecimal, what would it start with in ASCII? 
Se eu te contasse que uma palavra começa com 0x70 em hexadecimal, como ela começaria em ASCII?

Solução:
echo -n 0x70 | xxd -r -p
	p

Flag:
picoCTF{p}

Warmed Up | General Skills | 50 pontos

Descrição:
What is 0x3D (base 16) in decimal (base 10)?
Como fica 0x3D (hex) em decimal?

Solução:
printf "%d\n" 0x3D
	61

Flag:
picoCTF{61}

-----------------------------------------------------

2Warm | General Skills | 50 pontos

Descrição:
Can you convert the number 42(base 10) to binary (base2)?
Você pode coverter o número 42 (base10) para binário (base 2)?

Solução:
python3
bin(42)
	0b101010

Flag:
picoCTF{101010}

strings it | General Skills | 100 pontos

Descrição:
Can you find the flag in file without running it?
Você consegue achar a flag no arquivo sem executá-lo?

Solução:
wget https://jupiter.challenges.picoctf.org/static/fae9ac5267cd6e44124e559b901df177/strings
strings strings | grep pico
	picoCTF{5tRIng5_1T_7f766a23}

Flag:
picoCTF{5tRIng5_1T_7f766a23}

-----------------------------------------------------

Bases | General Skills | 100 pontos

Descrição:
What does this bDNhcm5fdGgzX3IwcDM1 mean? I think it has something to do with bases

Solução:
echo "bDNhcm5fdGgzX3IwcDM1" | base64 -d
	l3arn_th3_r0p35

Flag:
picoCTF{l3arn_th3_r0p35}

-----------------------------------------------------

First Grep | General Skills | 100 pontos

Descrição:
Can you find the flag in file? This would be really tedious to look through manually, something tells me there is a better way.
Você consegue achar a flag no arquivo? Isso seria tedioso de se fazer manualmente, algo me diz que tem uma maneira melhor.

Solução: 
wget https://jupiter.challenges.picoctf.org/static/515f19f3612bfd97cd3f0c0ba32bd864/file
cat file | grep pico
	picoCTF{grep_is_good_to_find_things_5af9d829}

Flag:
picoCTF{grep_is_good_to_find_things_5af9d829}
