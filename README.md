JPersianDate
============

Java Persian Date Library


Convert GregorianDate to PersianDate :

```
PersianDateTime pd = PersianDateTime.valueOf(new org.joda.time.DateTime(2013,3,3,10,20,30));
System.out.println("Persian Date : " + pd.toStirng());
System.out.println("Gregorian Date : " + pd.toGregorianDate());

```
