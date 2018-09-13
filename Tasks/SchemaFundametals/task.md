XSD Part 1: Schema fundamentals, creating a schema w/o namespace

XmlPractice / RawXmlPractice1.xml

1. Create a schema w/o namespace for the document
2. Make the document use the schema
3. Create a schema for the document, without restrictions at this point
Only a single root element should be available.
The series attribute should be required.
4. Add restrictions to make the total amount
 a. greater or equal to 0
 b. less than 1000000
 c. has two decimal digits
5. Enumeration - make the currency attribute accept either PLN or EUR
6. Restriction on strings - length - make the series attributes length (1,5)
7. Restriction on strings - regex - make the number attribute match the number pattern
8. Restrictions as globally defined simple types - redefine:
 a.  the currency attribute as a global simple type "currency"
 b. the totalamount elelemnt as a global simple type "invoiceAmount"
9. Add an annotation in (a) any element (b) any attribute, (c) in the currency enumeration, for both enumeration members


