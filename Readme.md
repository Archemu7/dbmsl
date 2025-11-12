1️) Index
🔹 Definition:
An index is a database object used to speed up data retrieval from a table.
🔹 Syntax:
CREATE INDEX index_name ON table_name(column_name);

2️)Sequence
🔹 Definition:

A sequence is an Oracle object that automatically generates numeric values, often used for primary keys.

🔹Syntax:
CREATE SEQUENCE sequence_name
START WITH 1
INCREMENT BY 1;

🔹 Example:
CREATE SEQUENCE emp_seq START WITH 1001 INCREMENT BY 1;

INSERT INTO emp (emp_no, emp_name, emp_salary)
VALUES ('E' || emp_seq.NEXTVAL, 'Arun', 50000);



3️) Synonym
🔹 Definition:

A synonym is an alias (nickname) for a database object — such as a table, view, or sequence.

🔹 Syntax:
CREATE SYNONYM synonym_name FOR original_object;

🔹 Example:
CREATE SYNONYM cust FOR new_view;










