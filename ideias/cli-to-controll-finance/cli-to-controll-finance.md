a cli to controll your finance:

sample commands:

~~~bash
finctl add expense <amount> <category> <description> today
finctl add income <amount> <category> <description> <date>
finctl add income <amount> <category> <description> <date>


finctl list expenses
finctl list expenses --category <category>
finctl list expenses --month <month>
finctl list expenses --year <year>
finctl list expenses --category <category> --month <month> --year <year>
finctl list expenses --category <category> --month <month> --year <year> --day <day>
finctl list expenses --category <category> --month <month> --year <year> --day <day> --description <description>


finctl edit expense <id> --amount <amount>
finctl edit expense <id> --category <category>
finctl edit expense <id> --description <description>
finctl edit expense <id> --day <date>

finctl delete expense <id>


finctl balance
finctl balance --category <category>
finctl balance --month <month>
finctl balance --year <year>
finctl balance --category <category> --month <month> --year <year>
finctl balance --category <category> --month <month> --year <year> --day <day>
finctl balance --category <category> --month <month> --year <year> --day <day> --description <description>
~~~