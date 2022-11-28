# :construction: Learning HoF / Aprendendo HoF ! :construction:

This project I learning use higher-order Functions of JavaScript! In `data.js` has an object with the keys:

<details><summary> species </summary> <br />
species => array of objects with keys:

- id: species id;
- name: name of species;
- popularity: number of species;
- location: where stay this species;
- residents => this is an array of objects with the keys:

- name;
- sex;
- age.

</details>

<details><summary> employees </summary> <br />
employees => array of objects with keys:

- id: employeer id;
- firstName: name of employeer;
- lastName: last name of employeer;
- managers: array of id, the elements are employees id;
- responsibleFor: species Id;

</details>

<details> <summary> hours </summary> <br />
hours => object, the keys is name of days week. In this keys has an object with two keys, open and close with a number.

</details>

<details><summary> prices </summary> <br />
prices => object with the keys, adult, senior and child, all keys has a decimal number.
</details>

<details><summary><strong> Português </summary></strong> <br />

Esse projeto eu consolidei meus conhecimentos com higher-order functions de JavaScript! Em `data.js` há um objeto com as chaves:

<details><summary> species </summary> <br />
species => um array de objects com as keys:

- id: id das especies;
- name: nome das especies;
- popularity: número de especies;
- location: onde ficam as especies;
- residents => um array de objetos com as chaves:

- name;
- sex;
- age.

</details>

<details><summary> employees </summary> <br />
employees => um array de objects com as keys:

- id: id dos empregados;
- firstName: nome do empregado;
- lastName: sobrenome do empregado;
- managers: array com id, os elementos são employees id;
- responsibleFor: species Id;

</details>

<details> <summary> hours </summary> <br />
 hours => object, as chaves são os dias da semana em inglês. Nessas chaves há um objeto com as chaves, open e close, que são números representando horas no formato de 24h.

</details>

<details><summary> prices </summary> <br />
prices => object com as chaves, adult, senior and child, todas as chaves possuem um decimal.
</details>

</details>

<details><summary><strong>Functions</summary></strong> <br />

<details><summary><strong> Function getSpeciesByIds </summary> </strong> <br />

This function get all species by ids. Recive an array of ids, then return an empth array if don't have less an id and and return an array with all species of all ids.

</details>

<details><summary><strong> Function getAnimalsOlderThan </strong></summary> <br />

Receve one species and one age, if all animals on the name of species have age more than this age return true, case at less one animal with age lower then the age return false.

</details>

<details><summary><strong> Function getEmployeeByName </summary></strong> <br />

This functions get a employeer by name. Receve a string with a name, this name can be the first name and the last name.

</details>

<details><summary><strong> function createEmployee </strong></summary> <br />

Receve an object with `id`, `firstName` and `lastName`, this param is `personalInfo`, receve another object with keys `managers` and `responsibleFor`, both are array and this param is `associatedWith`, then with this params create a new employee.

</details>

<details><summary><strong> function isManager </summary> </strong> <br />

This function return true or false, case receve `id` is manager return true, in other case return false.

</details>

<details><summary><strong> function addEmployee </summary></strong> <br />

This function can create a new employee like `createEmployee`, but receve `id`, `firstName`, `lastName`, `managers` and `responsibleFor`.

</details>

<details><summary><strong> function countAnimals </summary></strong> <br />

Can receve a species, if not have species return the number of all species.

If have one species return the number of this species.

</details>

<details><summary><strong> Function calculateEntry </summary></strong> <br />

Receve an object with keys `Adult`, `Child` and `Senior` this keys have a number, then will multiplication for prices, of object in `data.js`, then return the sum.

</details>

<details><summary><strong> Function getAnimalMap </summary></strong> <br />

Can receve an object with keys:

- includeNames;
- sorted;
- sex.

If includeNames is true return all animals and your names.

If sorted is true return all animals sorted.

If sex is male return all male animals, and if is female return all female animals.

</details>

<details><strong> Function getSchedule </summary></strong> <br />

Can receve a param this is a string with a day name.

If not receve a param return `"Open from ${open} am until ${close}pm"` for all day.

If receve a day return `"Open from ${open} am until ${close}pm"`.

If the day is monday return `"CLOSED"`.

</details>

<details><summary><strong>  Function getOldestFromSpecies </summary></strong> <br />

Receve an id of employee and return an array with name, sex and age of the oldest animal. This animal is the first animal of the first specie in array, responsibleFor of employee.

</details>

<details><summary><strong> Function increasePrices </summary></strong> <br />

Receve a number, then change prices in `data.js`.

This change increase the price in number in percentage.

</details>

<details><summary><strong> Function getEmployeeCoverage </summary></strong> <br />

Can receve `id`, `firstName` or `lastName`.

If don't receve a param return an object with all employees, the keys are the full name and all keys receve all animals name.

If receve a param return an object  with one key, the full name of param employee. This key have name of all animal of this employee.

</details>

</details>

<details><summary><strong>Português: Funções</summary></strong> <br />

<details><summary><strong> Função getSpeciesByIds </summary> </strong> <br />

Essa função pega todas das espécies dos ids. Recebe um array de ids, então retorna um array vazio se não há pelo menos um id e um array com todos das espécies de todos os ids.

</details>

<details><summary><strong> Função getAnimalsOlderThan </strong></summary> <br />

Recebe uma espécie e uma idade, se todos os animais da espécie tiver uma idade maior que a idade enviada a função retorna true, caso pelo menos um animal tenha uma idade menor retorna false.

</details>

<details><summary><strong> Função createEmployee </strong></summary> <br />

Recebe um objeto com as chaves `id`, `firstName` e `lastName`, para o parámetro `personalInfo`, recebe um obejeto com as chaves `managers` e `responsibleFor`, ambos são array e esse parámetro é `associatedWith`, então com esses parámetro cria-se um novo empregado.

</details>


<details><summary><strong> Função isManager </summary> </strong> <br />

Essa função retorna true ou false, caso o `id` recebido seja um gerente retorna true, em outro caso retorna false.

</details>

<details><summary><strong> Função addEmployee </summary></strong> <br />

Essa função pode criar um novo empregado como a função `createEployee`, mas essa função recebe `id`, `firstName`, `lastName`, `managers` e `responsibleFor`.

</details>

<details><summary><strong> Função countAnimals </summary></strong> <br />

Pode receber uma espécie, se não receber, retorna o número de todos os animais de todas as espécies.

Se tem uma espécie retorna o número de animais dessa espécie.

</details>

<details><summary><strong> Função calculateEntry </summary></strong> <br />

Recebe um objeto com as chaves `Adult`, `Child` e `Senior` essas chaves têm um número, Então esses números são multiplicados pelos prices, do objeto `data.js`, então retorna a soma.

</details>

<details><summary><strong> Função getAnimalMap </summary></strong> <br />

Pode receber um objeto com as chaves:

- includeNames;
- sorted;
- sex.

Se includeNames for true retorna todos animais e seus nomes.

Se sorted for true retorna todos animais ordenados.

Se sex for male retorna todos os animais macho, e se for female retorna todos animais feminino.

</details>

<details><strong> Função getSchedule </summary></strong><br />

Pode receber um parâmetro sendo um string com os dias da semana em inglês.

Se não receber um parâmetro retorna `"Open from ${open} am until ${close}pm"` para todos os dias.

Se receber um dia retorna `"Open from ${open} am until ${close}pm"`.

Se o dia for segunda-feira (monday) retorna `"CLOSED"`.

</details>

<details><summary><strong>  Função getOldestFromSpecies </summary></strong> <br />

Recebe um id do empregado e retorna um array com nome, sexo e idade do animal mais velho. Esse animal é o primeiro animal da primeira espécie no array responsibleFor do empregado.

</details>

<details><summary><strong> Função increasePrices </summary></strong> <br />

Recebe um númerom então muda os preços em prices no arquivo `data.js`.

Essa mudanção é um incremento com o número em percentagem.

</details>

<details><summary><strong> Função getEmployeeCoverage </summary></strong> <br />

Pode receber `id`, `firstName` ou `lastName`.

Se não receber um parâmetro retorna um objeto com todos os empregados, as chaves são o nome completo de todos os funcionários, as chaves possuem os nomes dos animais.

Se recebe um parâmetro retorna um objeto com uma chave, o nome completo do empregado enviado como parâmetro. Essa chave possui todos os animais do empregado.

</details>

</details>