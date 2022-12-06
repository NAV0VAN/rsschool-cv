
## Name
Alexey Neuymin
## Contacts for communication
a.neuymin@mail.ru
## About Me
I am a curious person interested in programming
## Skills
JavaScript, Node.js, HTML, CSS, Bootstrap
## Code examples
```
const copy = async () => {
    try {
        if (existsSync(folderNameTo)) {
            throw new Error("FS operation failed (existsSync())")
        }
        mkdir(folderNameTo, { recursive: false }).catch((err) => {
            throw new Error('FS operation failed (mkdir())');
        }
        );
        const files = await readdir(folderNameFrom).catch((err) => {
            throw new Error('ERROR readdtr');
        })
        for (const file of files) {
          ...
            }
            );
        }
    } catch (error) {
        console.error(error)
    }
};

await copy();
```
## Work experience
No work experience
## Education
High school and university
## English language level
А1. Breakthrough or beginner
