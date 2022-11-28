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

<details><summary><strong>functions</summary></strong> <br />

<details><summary><strong> Function getSpeciesByIds </summary> </strong> <br />

This function get all species by ids. Recive an array of ids, then return an empth array if no id, an array with the species of id and return an array with all species of all ids.

</details>

<details><summary><strong> Function getAnimalsOlderThan </strong></summary>

Receve one species and one age, if all animals on the name of species have age more than this age return true, case at less one animal with age lower then the age return false.

</details>

<details><summary><strong> Function getEmployeeByName </summary></strong>

This functions get a employeer by name. Receve a string with a name, this name can be the first name and the last name.

</details>

<details><summary><strong> function createEmployee </strong></summary>

Receve an object with `id`, `firstName` and `lastName`, this param is `personalInfo`, receve another object with keys `managers` and `responsibleFor`, both are array and this param is `associatedWith`, then with this params create a new employee.

</details>

<details><summary><strong> function isManager </summary> </strong>

This function return true or false, case receve `id` is manager return true, in other case return false.

</details>

<details><summary><strong> function addEmployee </summary></strong>

This function can create a new employee like `createEmployee`, but receve `id`, `firstName`, `lastName`, `managers` and `responsibleFor`.

</details>

<details><summary><strong> function countAnimals </summary></strong>

Can receve a species, if not have species return the number of all species.

If have one species return the number of this species.

</details>

<details><summary><strong> function calculateEntry </summary></strong>

Receve an object with keys `Adult`, `Child` and `Senior` this keys have a number, then will multiplication for prices, a key of object in `data.js`, then return the sum.

</details>

<details><summary><strong> function getAnimalMap </summary></strong>

Can receve an object with keys:

- includeNames;
- sorted;
- sex.

If includeNames is true return all animals and your names.

If sorted is true return all animals sorted.

If sex is male return all male animals, and if is female return all female animals.
github.com:ladcs/learning-HoF-js.git><strong> function getSchedule </summary></strong>

Can receve a param this is a string with a day name.

If not receve a param return `"Open from ${open} am until ${close}pm"` for all day.

If receve a day return `"Open from ${open} am until ${close}pm"`.

If the day is monday return `"CLOSED"`.

</details>

<details><summary><strong>  function getOldestFromSpecies </summary></strong>

Receve an id of employee and return an array with name, sex and age of the oldest animal. This animal is the first animal of the first specie in array, responsibleFor of employee.

</details>

<details><summary><strong> function increasePrices </summary></strong>

Receve a number, then change prices in `data.js`.

This change increase the price in number in percentage.

</details>

<details><summary><strong> function getEmployeeCoverage </summary></strong>

Can receve `id`, `firstName` or `lastName`.

If don't receve a param return an object with all employees, the keys are the name (first name and last name), and all animals name.

If receve a param return an object  with one key, the name of employee (first name and last name), this employee of param. this key have name of all animal of this employee.

</details>

</details>
