# Mikalai Alikhnovich
# Contacts
* Phone: +375 (29) 313-68-20
* E-mail: v3136820@gmail.com
* Github: [Nickoff](https://github.com/nickoff)
# About me
Hello. I am 38 years old. I work in developer company. Programming is my hobby.
# Education
Major - Architecture
Belarusian National Technical University
2001-2007
# Skills
* HTML (basic)
* CSS (basic)
* JS (basic)
* Python (basic)
# Courses
* JavaScript/Front-end Pre-School 2022Q4 [Certificate](https://app.rs.school/certificate/18cosizf)
* Python (basic) [Stepik](https://stepik.org/cert/986358)
* JavaScript/Front-end 2023Q1 (in the process)
# Code
  ```
    function convert(input, source, target) {
      outputDec = 0;
      index = 0;
      output = [];
      for (i = input.length - 1; i >= 0; i--) {
        outputDec += (source.indexOf(input[index]) * (source.length ** i));
        index += 1;
    }
    if (outputDec == 0) {return target[0]}
    else { while (outputDec > 0) {
      output.push(target[outputDec % target.length]);
      outputDec = Math.floor(outputDec / target.length);
    }
    return output.reverse().join('')}
  }
  ```
# Languages
* Belarusian - native
* Russian - native
* English - A1
# Experience
[Plants](https://rolling-scopes-school.github.io/nickoff-JSFEPRESCHOOL2022Q4/plants/)
