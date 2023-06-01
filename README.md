<h1> Filip Lichovski 213086 </h1>
 
![Untitled Diagram drawio](https://github.com/Filiplico/SI_2023_lab2_213086/assets/117199127/3f777eeb-3e23-4b58-91ac-426902642e2d)

<h2> Цикломатска комплексност </h2>

Цикломатксата комплексност на Control Flow графот ја добив со броење на регионите и според тоа е 11.

<h2> Тестови според Every branch критериумот </h2>

Test case 1: Username == null </br>
Test case 2: Password == null </br>
Test case 3: Email == null </br>
Test case 4: Има дупликат username и дупликат email во листата на user-и
Test case 5: Password има празно место </br>
Test case 6: Password без специјални карактери </br>
Test case 7: Email-от не содржи "@" и "." </br>
Test case 8: Password-от го содржи Username-от или е помал од 8 карактери

<h2> Тестови според Multiple condition критериумот </h2>

За Multiple Condition критериумот треба да ги разгледаме сите можни комбинации на услови во if (user==null || user.getPassword()==null || user.getEmail()==null).

Test case 1: Не постои User </br>
Test case 2: има Username, нема Password, има Email </br>
Test case 3: има Username, има Password, нема Email </br>
Test case 4: има Username, има Password, има Email </br>
Test case 5: нема Username, нема Password, нема Email </br>
