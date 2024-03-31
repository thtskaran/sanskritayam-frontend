# Sanskritayam 

Sanskritayam is a fun and experimental programming language inspired by Sanskrit, the ancient language of India. This project was created based on a viral meme from last year, where a group of aunties were discussing the idea of making Sanskrit a coding language. As a joke, my friend [Pinakkk](https://github.com/pinakkk) and I [Karan](https://github.com/thtskaran) thought of turning this idea into reality, and thus, Sanskritayam was born!

![Sanskritayam Programming Language](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhlAeRIG9cCOOVfbhmSn09xLNnJ_8gwoAoaj6D73czsYaWokpnayLG5CJu6UBQFrgun1DBPlRw4Gyl2aEU5_33ZBj9XlxFVk9pmoqiJeuTTSmsxG3UKFW184ZzXYSGOY4Ra4GkGHjtY6M1yRsgRz0ZNXrS57c32EFXTQSYwHSNMktzZSi3a_m0Mflw4Gec/s1173/A%20Banner%20image%20for%20a%20programming%20language%20based%20on%20sanskrit%20,%20ancient%20scriptures%20,%20programming%20icons%20and%20references%20,%20vedic%20culture%20.png)

Please note that Sanskritayam is not intended for serious production use and comes with no warranty. It's a purely recreational project meant for learning and entertainment purposes.

## Features

- Sanskrit-inspired syntax and keywords
- Basic programming constructs like variables, conditionals, loops, and functions
- Support for common data types such as integers, floats, strings, lists, and dictionaries
- File I/O operations
- Exception handling
- Object-oriented programming concepts
- Write "Swaha" to have some extra fun!

## Getting Started

To get started with Sanskritayam, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/thtskaran/sanskritayam.git
   ```
2. Install Python 3.x if you haven't already.

3. Navigate to the directory containing the setup.py file:
   ```
   cd sanskritayam
   ```
4. Install the Sanskritayam interpreter:
   ```
   pip install -e .
   ```

Alternatively, you can install the latest release from PyPI using the following command:
```
pip install sanskritayam
```

## Executing .skt Files

Once you have installed Sanskritayam, you can execute .skt files in the following ways:

1. Non-Sudo Installation:
   If you didn't use `sudo` privileges while installing Sanskritayam, it won't be in your `$PATH`. Use the following command to execute .skt files:
   ```
   python -m sanskritayam <filename.skt>
   ```

2. Sudo Installation:
   If you used `sudo` while installing Sanskritayam, you can execute .skt files directly without explicitly using `python -m`:
   ```
   sanskritayam <filename.skt>
   ```

## Updating Sanskritayam

To update your local installation of Sanskritayam with the latest changes from GitHub, follow these steps:

1. Pull the latest changes from GitHub:
   ```
   git pull origin main
   ```
   Replace `main` with the name of the branch that contains the updated Sanskritayam interpreter, if it's not the main branch.

2. Reinstall the Sanskritayam interpreter:
   ```
   pip install --upgrade --force-reinstall -e .
   ```

Alternatively, you can update to the latest release from PyPI using the following command:
```
pip install --upgrade sanskritayam
```

## Documentation

# Sanskritayam Language Documentation

This document provides a detailed overview of the Sanskritayam programming language, including its syntax, keywords, and features.

## Syntax Mapping

The following table maps Python syntax to the corresponding Sanskritayam syntax:

- The swaha ability is an unique ability, and you can try writing swaha after writing printayam or when calling a function.
- Note:
  - You should not use swaha inside any functions or in if(yadi) and else(anyatha) conditions.

| Python | Sanskritayam |
| --- | --- |
| ; | swaha |
| print | printayam swaha|
| input | pravesham |
| if | yadi |
| else | anyatha |
| for | krte |
| while | jabtak |
| def | paribhasha |
| return | pratyahar |
| and | cha |
| or | va |
| not | na |
| True | satyam |
| False | asatyam |
| None | kimapi_na |
| in | antargatam |
| is | asti |
| = | samam |
| + | yogah |
| - | viyogah |
| * | gunanam |
| / | bhagaharah |
| // | poornabhagaharah |
| % | sheshah |
| ** | ghatah |
| < | nyoonam |
| > | adhikam |
| <= | nyoonasamam |
| >= | adhikasamam |
| == | tulyam |
| != | atulyam |
| try | prayatnah |
| except | apavadah |
| finally | antatah |
| raise | utthapanam |
| import | ayatah |
| from | tah |
| as | yatha |
| with | saha |
| assert | pratijna |
| class | vargah |
| del | vilopanam |
| elif | athavayadi |
| global | vaishvikam |
| lambda | lambda |
| pass | gachha |
| yield | yield |

## Variables and Data Types

In Sanskritayam, variables are declared using the = operator, which is represented as samam. The following data types are supported:

- Integers (ganakah): Whole numbers, e.g., 10, -5.
- Floats (chhedakah): Decimal numbers, e.g., 3.14, -2.7.
- Strings (aksharankhyata): Sequences of characters enclosed in single or double quotes, e.g., 'hello', "world".
- Lists (samhata): Ordered collections of items, e.g., [1], ['apple', 'banana', 'cherry'].
- Dictionaries (nirukti): Unordered collections of key-value pairs, e.g., {'name': 'John', 'age': 30}.

Example:

```
ganakah = 42
chhedakah = 3.14
aksharankhyata = "sanskritayam"
samhata = [1, 2, 3, 4, 5]
nirukti = {'key1': 'value1', 'key2': 'value2'}
```

## Control Flow

Sanskritayam supports control flow statements like conditional statements and loops.

### Conditional Statements

Conditional statements in Sanskritayam use the yadi (if), anyatha (else), and athavayadi (elif) keywords.

Example:

```
ganakah = 10

yadi ganakah > 0:
    printayam("ganakah asti dhanak")
anyatha:
    printayam("ganakah asti rnnak")
```

### Loops

Sanskritayam provides two types of loops: krte (for) and jabtak (while).

#### For Loops

The krte loop is used to iterate over a sequence (e.g., a list or a string).

Example:

```
aksharankhyata = "sanskritayam"

krte varna antargatam aksharankhyata:
    printayam(varna)
```

#### While Loops

The jabtak loop is used to repeatedly execute a block of code as long as a given condition is true.

Example:

```
ganakah = 0

jabtak ganakah < 5:
    printayam(ganakah)
    ganakah = ganakah + 1
```

## Functions

Functions in Sanskritayam are defined using the paribhasha keyword, and arguments are passed within parentheses. The pratyahar keyword is used to return a value from the function.

Example:

```
paribhasha yogah(x, y):
    ganakah = x + y
    pratyahar ganakah

printayam(yogah(3, 4))  # Output: 7
```

## File I/O

Sanskritayam supports reading from and writing to files using the ayatah (import) keyword and the yatha (as) keyword.

### Reading from a File

Example:

```
ayatah "file.txt", "r" yatha patham:
    samgraham = patham.read()
    printayam(samgraham)
```

### Writing to a File

Example:

```
ayatah "file.txt", "w" yatha lekhyam:
    lekhyam.write("This is some text.")
```

## Exception Handling

Sanskritayam provides exception handling capabilities using the prayatnah (try), apavadah (except), and antatah (finally) keywords.

Example:

```
prayatnah:
    ganakah = 10 / 0
apavadah ZeroDivisionError:
    printayam("Zero dvaara vibhajanam akarmyam")
antatah:
    printayam("Exception handling samaptam")
```

## Object-Oriented Programming

Sanskritayam supports object-oriented programming concepts like classes and objects using the vargah (class) keyword.

Example:

```
vargah Vyakti:
    paribhasha __init__(svayam, nama, vayah):
        svayam.nama = nama
        svayam.vayah = vayah

    paribhasha paricchedam(svayam):
        printayam(f"Nama: {svayam.nama}, Vayah: {svayam.vayah}")

vyakti = Vyakti("John", 30)
vyakti.paricchedam()  # Output: Nama: John, Vayah: 30
```

## Examples

You can find various example programs written in Sanskritayam in the [Examples](https://github.com/thtskaran/sanskritayam/tree/main/examples) directory. These examples demonstrate different aspects of the language and serve as a starting point for learning Sanskritayam.

## Testing

To ensure the correctness and reliability of the Sanskritayam language, a comprehensive test suite is available in the [Tests](https://github.com/thtskaran/sanskritayam/tree/main/tests) directory. The test suite covers various language features and helps maintain the integrity of the language implementation.

To run the tests, execute the following command:
```
python -m skm tests/sanskritayam_comprehensive_test.skt
```

## License

The Sanskritayam programming language is released under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0). Feel free to use, modify, and distribute the language according to the terms of the license.

## Disclaimer

Sanskritayam is a joke programming language created for fun and learning purposes. It is not recommended for use in production environments, and no warranty or support is provided. Use it at your own risk!

If anyone feels offended or uncomfortable with the concept or any aspect of this project, we sincerely apologize. Our intention is not to mock or disrespect any language, culture, political party, or religion. It's purely a lighthearted attempt to explore the idea of creating a programming language based on Sanskrit.

## Acknowledgements

We would like to acknowledge the creators of the viral meme that inspired this project. Their humorous discussion sparked the idea of creating Sanskritayam, and we are grateful for the laughter and inspiration they provided.

Special thanks to [Pinakkk](https://github.com/pinakkk) and [Karan](https://github.com/thtskaran) for their invaluable contributions and collaboration in bringing Sanskritayam to life. Their creativity, technical expertise, and sense of humor have been instrumental in shaping this project.

We also want to acknowledge that we may have unintentionally caused offense or hurt sentiments with this project. We deeply apologize if this is the case. 

## Contributing

As Sanskritayam is a fun and experimental project, we welcome contributions from the community. If you have any ideas, suggestions, or improvements, feel free to open an issue or submit a pull request on the [GitHub repository](https://github.com/thtskaran/sanskritayam).

Let's have fun coding in Sanskritayam and embrace the quirks and joys of this unique language!