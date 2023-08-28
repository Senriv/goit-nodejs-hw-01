# Получаем и выводим весь список контактов в виде таблицы (console.table)
node index.js --action list
https://monosnap.com/file/uNEDXQnY3cgRQxeeQKBQ8CYeu1bFq5

# Получаем контакт по id - выводим в консоль объект контакта или null, если контакта с таким id не существует.
node index.js --action get --id 05olLMgyVQdWRwgKfg5J6
https://monosnap.com/file/A39ZbuvaVz2iCVUQ0mmcbWWR69Bff0

# Добавляем контакт и выводим в консоль созданный контакт
node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22
https://monosnap.com/file/zBWJyVv02iDzSiDEY3os9YINuLurqH

# Удаляем контакт и выводим в консоль удаленный контакт или null, если контакта с таким id не существует.
node index.js --action remove --id qdggE76Jtbfd9eWJHrssH
https://monosnap.com/file/eIE2CqjPuU3yJlGaTCeM5oPDLspTJY