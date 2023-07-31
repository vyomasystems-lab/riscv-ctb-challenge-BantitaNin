# riscv_ctb_challenges
level1
challeng_1_logical
![image](https://github.com/vyomasystems-lab/riscv-ctb-challenge-BantitaNin/assets/131229638/93c6e36c-365f-4e99-af8a-d75e6a314f9a)
the bug occur when use andi and z4 because there's no instruction name or z4 so I change to and then changed z4 to s4

challenge_2_loop
![image](https://github.com/vyomasystems-lab/riscv-ctb-challenge-BantitaNin/assets/131229638/1964e2b7-8e73-4e3c-b7bf-9a402b310c22)
the loop doesn't end because if those test nums are equal it will just go back to the same loop and continue so I make it complete with success and it will add three times then finished

challenge_3_illegal
![image](https://github.com/vyomasystems-lab/riscv-ctb-challenge-BantitaNin/assets/131229638/62956103-0308-4468-a62b-9f25deea4f3f)
it's illeagal because it has .word 0 so I change it into adding test num together

level2 
chellange1_instruction
![image](https://github.com/vyomasystems-lab/riscv-ctb-challenge-BantitaNin/assets/131229638/f99cd8e6-4ac8-4f1c-b9c9-253454c0b6aa)
it's illegal because we use 32 bits but one of the 64 bits was enabled so I made it 0 to unenable it

challenge2_exceptions
![image](https://github.com/vyomasystems-lab/riscv-ctb-challenge-BantitaNin/assets/131229638/5907b658-1c90-400d-bcd3-111bcc605874)

we have to create config.yaml file so I create it and make it show 9 of the exceptions
