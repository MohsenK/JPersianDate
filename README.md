JPersianDate
============

Java Persian Date Library


Convert GregorianDate to PersianDate :

```
PersianDateTime pd = PersianDateTime.valueOf(new GregorianCalendar(2013,3,3,10,20,30));
System.out.println("Persian Date : " + pd.toStirng());
System.out.println("Gregorian Date : " + pd.toGregorianDate().get(Calendar.YEAR) + "/" + pd.toGregorianDate().get(Calendar.MONTH) + "/" + pd.toGregorianDate().get(Calendar.DAY_OF_MONTH));

```
