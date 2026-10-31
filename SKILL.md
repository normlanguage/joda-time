# joda.time Skill

Use this skill to work with Norm module `joda.time` version 4. Use only declarations listed below.

## `joda.time`

Source: `Chronology.norm`

### `Chronology`

```norm
class Chronology
```

#### `Chronology`

```norm
Chronology(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `joda.time`

Source: `DateTime.norm`

### `DateTime`

```norm
class DateTime extends BaseDateTime implements ReadableDateTime, Serializable, ReadableInstant
```

#### `DateTime`

```norm
DateTime(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `getDayOfMonth`

```norm
Integer getDayOfMonth()
```

Returns: `Integer`

#### `getDayOfWeek`

```norm
Integer getDayOfWeek()
```

Returns: `Integer`

#### `getHourOfDay`

```norm
Integer getHourOfDay()
```

Returns: `Integer`

#### `getMillis`

```norm
Long getMillis()
```

Returns: `Long`

#### `getMinuteOfHour`

```norm
Integer getMinuteOfHour()
```

Returns: `Integer`

#### `getMonthOfYear`

```norm
Integer getMonthOfYear()
```

Returns: `Integer`

#### `getSecondOfMinute`

```norm
Integer getSecondOfMinute()
```

Returns: `Integer`

#### `getYear`

```norm
Integer getYear()
```

Returns: `Integer`

#### `getZone`

```norm
DateTimeZone? getZone()
```

Returns: `DateTimeZone?`

#### `minusDays`

```norm
DateTime? minusDays(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `DateTime?`

#### `minusHours`

```norm
DateTime? minusHours(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `DateTime?`

#### `minusMinutes`

```norm
DateTime? minusMinutes(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `DateTime?`

#### `minusMonths`

```norm
DateTime? minusMonths(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `DateTime?`

#### `minusSeconds`

```norm
DateTime? minusSeconds(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `DateTime?`

#### `minusWeeks`

```norm
DateTime? minusWeeks(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `DateTime?`

#### `minusYears`

```norm
DateTime? minusYears(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `DateTime?`

#### `plusDays`

```norm
DateTime? plusDays(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `DateTime?`

#### `plusHours`

```norm
DateTime? plusHours(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `DateTime?`

#### `plusMinutes`

```norm
DateTime? plusMinutes(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `DateTime?`

#### `plusMonths`

```norm
DateTime? plusMonths(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `DateTime?`

#### `plusSeconds`

```norm
DateTime? plusSeconds(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `DateTime?`

#### `plusWeeks`

```norm
DateTime? plusWeeks(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `DateTime?`

#### `plusYears`

```norm
DateTime? plusYears(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `DateTime?`

#### `toLocalDate`

```norm
LocalDate? toLocalDate()
```

Returns: `LocalDate?`

#### `toLocalDateTime`

```norm
LocalDateTime? toLocalDateTime()
```

Returns: `LocalDateTime?`

#### `toLocalTime`

```norm
LocalTime? toLocalTime()
```

Returns: `LocalTime?`

#### `toString`

```norm
String? toString()
```

Returns: `String?`

#### `withDate`

```norm
DateTime? withDate(Integer arg0, Integer arg1, Integer arg2)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `Integer`
- `arg2`: `Integer`

Returns: `DateTime?`

#### `withDate`

```norm
DateTime? withDate(LocalDate? arg0)
```

Parameters:

- `arg0`: `LocalDate?`

Returns: `DateTime?`

#### `withTime`

```norm
DateTime? withTime(Integer arg0, Integer arg1, Integer arg2, Integer arg3)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `Integer`
- `arg2`: `Integer`
- `arg3`: `Integer`

Returns: `DateTime?`

#### `withTime`

```norm
DateTime? withTime(LocalTime? arg0)
```

Parameters:

- `arg0`: `LocalTime?`

Returns: `DateTime?`

#### `withTimeAtStartOfDay`

```norm
DateTime? withTimeAtStartOfDay()
```

Returns: `DateTime?`

#### `withZone`

```norm
DateTime? withZone(DateTimeZone? arg0)
```

Parameters:

- `arg0`: `DateTimeZone?`

Returns: `DateTime?`

#### `withZoneRetainFields`

```norm
DateTime? withZoneRetainFields(DateTimeZone? arg0)
```

Parameters:

- `arg0`: `DateTimeZone?`

Returns: `DateTime?`

### `dateTimeNew`

```norm
DateTime dateTimeNew(Integer arg0, Integer arg1, Integer arg2, Integer arg3, Integer arg4)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `Integer`
- `arg2`: `Integer`
- `arg3`: `Integer`
- `arg4`: `Integer`

Returns: `DateTime`

### `dateTimeNew`

```norm
DateTime dateTimeNew(Long arg0)
```

Parameters:

- `arg0`: `Long`

Returns: `DateTime`

### `dateTimeNow`

```norm
DateTime? dateTimeNow()
```

Returns: `DateTime?`

### `dateTimeNow`

```norm
DateTime? dateTimeNow(Chronology? arg0)
```

Parameters:

- `arg0`: `Chronology?`

Returns: `DateTime?`

### `dateTimeNow`

```norm
DateTime? dateTimeNow(DateTimeZone? arg0)
```

Parameters:

- `arg0`: `DateTimeZone?`

Returns: `DateTime?`

### `dateTimeParse`

```norm
DateTime? dateTimeParse(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `DateTime?`

## `joda.time`

Source: `DateTimeConstants.norm`

### `DateTimeConstants`

```norm
class DateTimeConstants
```

#### `DateTimeConstants`

```norm
DateTimeConstants(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

### `dateTimeConstantsFieldGetApril`

```norm
Integer dateTimeConstantsFieldGetApril()
```

Returns: `Integer`

### `dateTimeConstantsFieldGetAugust`

```norm
Integer dateTimeConstantsFieldGetAugust()
```

Returns: `Integer`

### `dateTimeConstantsFieldGetDaysPerWeek`

```norm
Integer dateTimeConstantsFieldGetDaysPerWeek()
```

Returns: `Integer`

### `dateTimeConstantsFieldGetDecember`

```norm
Integer dateTimeConstantsFieldGetDecember()
```

Returns: `Integer`

### `dateTimeConstantsFieldGetFebruary`

```norm
Integer dateTimeConstantsFieldGetFebruary()
```

Returns: `Integer`

### `dateTimeConstantsFieldGetFriday`

```norm
Integer dateTimeConstantsFieldGetFriday()
```

Returns: `Integer`

### `dateTimeConstantsFieldGetHoursPerDay`

```norm
Integer dateTimeConstantsFieldGetHoursPerDay()
```

Returns: `Integer`

### `dateTimeConstantsFieldGetJanuary`

```norm
Integer dateTimeConstantsFieldGetJanuary()
```

Returns: `Integer`

### `dateTimeConstantsFieldGetJuly`

```norm
Integer dateTimeConstantsFieldGetJuly()
```

Returns: `Integer`

### `dateTimeConstantsFieldGetJune`

```norm
Integer dateTimeConstantsFieldGetJune()
```

Returns: `Integer`

### `dateTimeConstantsFieldGetMarch`

```norm
Integer dateTimeConstantsFieldGetMarch()
```

Returns: `Integer`

### `dateTimeConstantsFieldGetMay`

```norm
Integer dateTimeConstantsFieldGetMay()
```

Returns: `Integer`

### `dateTimeConstantsFieldGetMillisPerDay`

```norm
Integer dateTimeConstantsFieldGetMillisPerDay()
```

Returns: `Integer`

### `dateTimeConstantsFieldGetMillisPerHour`

```norm
Integer dateTimeConstantsFieldGetMillisPerHour()
```

Returns: `Integer`

### `dateTimeConstantsFieldGetMillisPerMinute`

```norm
Integer dateTimeConstantsFieldGetMillisPerMinute()
```

Returns: `Integer`

### `dateTimeConstantsFieldGetMillisPerSecond`

```norm
Integer dateTimeConstantsFieldGetMillisPerSecond()
```

Returns: `Integer`

### `dateTimeConstantsFieldGetMinutesPerHour`

```norm
Integer dateTimeConstantsFieldGetMinutesPerHour()
```

Returns: `Integer`

### `dateTimeConstantsFieldGetMonday`

```norm
Integer dateTimeConstantsFieldGetMonday()
```

Returns: `Integer`

### `dateTimeConstantsFieldGetNovember`

```norm
Integer dateTimeConstantsFieldGetNovember()
```

Returns: `Integer`

### `dateTimeConstantsFieldGetOctober`

```norm
Integer dateTimeConstantsFieldGetOctober()
```

Returns: `Integer`

### `dateTimeConstantsFieldGetSaturday`

```norm
Integer dateTimeConstantsFieldGetSaturday()
```

Returns: `Integer`

### `dateTimeConstantsFieldGetSecondsPerMinute`

```norm
Integer dateTimeConstantsFieldGetSecondsPerMinute()
```

Returns: `Integer`

### `dateTimeConstantsFieldGetSeptember`

```norm
Integer dateTimeConstantsFieldGetSeptember()
```

Returns: `Integer`

### `dateTimeConstantsFieldGetSunday`

```norm
Integer dateTimeConstantsFieldGetSunday()
```

Returns: `Integer`

### `dateTimeConstantsFieldGetThursday`

```norm
Integer dateTimeConstantsFieldGetThursday()
```

Returns: `Integer`

### `dateTimeConstantsFieldGetTuesday`

```norm
Integer dateTimeConstantsFieldGetTuesday()
```

Returns: `Integer`

### `dateTimeConstantsFieldGetWednesday`

```norm
Integer dateTimeConstantsFieldGetWednesday()
```

Returns: `Integer`

## `joda.time`

Source: `DateTimeFormat.norm`

### `DateTimeFormat`

```norm
class DateTimeFormat
```

#### `DateTimeFormat`

```norm
DateTimeFormat(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

### `dateTimeFormatForPattern`

```norm
DateTimeFormatter? dateTimeFormatForPattern(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `DateTimeFormatter?`

### `dateTimeFormatForStyle`

```norm
DateTimeFormatter? dateTimeFormatForStyle(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `DateTimeFormatter?`

### `dateTimeFormatFullDate`

```norm
DateTimeFormatter? dateTimeFormatFullDate()
```

Returns: `DateTimeFormatter?`

### `dateTimeFormatFullDateTime`

```norm
DateTimeFormatter? dateTimeFormatFullDateTime()
```

Returns: `DateTimeFormatter?`

### `dateTimeFormatFullTime`

```norm
DateTimeFormatter? dateTimeFormatFullTime()
```

Returns: `DateTimeFormatter?`

### `dateTimeFormatLongDate`

```norm
DateTimeFormatter? dateTimeFormatLongDate()
```

Returns: `DateTimeFormatter?`

### `dateTimeFormatLongDateTime`

```norm
DateTimeFormatter? dateTimeFormatLongDateTime()
```

Returns: `DateTimeFormatter?`

### `dateTimeFormatLongTime`

```norm
DateTimeFormatter? dateTimeFormatLongTime()
```

Returns: `DateTimeFormatter?`

### `dateTimeFormatMediumDate`

```norm
DateTimeFormatter? dateTimeFormatMediumDate()
```

Returns: `DateTimeFormatter?`

### `dateTimeFormatMediumDateTime`

```norm
DateTimeFormatter? dateTimeFormatMediumDateTime()
```

Returns: `DateTimeFormatter?`

### `dateTimeFormatMediumTime`

```norm
DateTimeFormatter? dateTimeFormatMediumTime()
```

Returns: `DateTimeFormatter?`

### `dateTimeFormatShortDate`

```norm
DateTimeFormatter? dateTimeFormatShortDate()
```

Returns: `DateTimeFormatter?`

### `dateTimeFormatShortDateTime`

```norm
DateTimeFormatter? dateTimeFormatShortDateTime()
```

Returns: `DateTimeFormatter?`

### `dateTimeFormatShortTime`

```norm
DateTimeFormatter? dateTimeFormatShortTime()
```

Returns: `DateTimeFormatter?`

## `joda.time`

Source: `DateTimeFormatter.norm`

### `DateTimeFormatter`

```norm
class DateTimeFormatter
```

#### `DateTimeFormatter`

```norm
DateTimeFormatter(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `getDefaultYear`

```norm
Integer getDefaultYear()
```

Returns: `Integer`

#### `getZone`

```norm
DateTimeZone? getZone()
```

Returns: `DateTimeZone?`

#### `isOffsetParsed`

```norm
Boolean isOffsetParsed()
```

Returns: `Boolean`

#### `isParser`

```norm
Boolean isParser()
```

Returns: `Boolean`

#### `isPrinter`

```norm
Boolean isPrinter()
```

Returns: `Boolean`

#### `parseDateTime`

```norm
DateTime? parseDateTime(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `DateTime?`

#### `parseLocalDate`

```norm
LocalDate? parseLocalDate(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `LocalDate?`

#### `parseLocalDateTime`

```norm
LocalDateTime? parseLocalDateTime(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `LocalDateTime?`

#### `parseLocalTime`

```norm
LocalTime? parseLocalTime(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `LocalTime?`

#### `parseMillis`

```norm
Long parseMillis(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Long`

#### `print`

```norm
String? print(ReadableInstant? arg0)
```

Parameters:

- `arg0`: `ReadableInstant?`

Returns: `String?`

#### `print`

```norm
String? print(ReadablePartial? arg0)
```

Parameters:

- `arg0`: `ReadablePartial?`

Returns: `String?`

#### `withDefaultYear`

```norm
DateTimeFormatter? withDefaultYear(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `DateTimeFormatter?`

#### `withOffsetParsed`

```norm
DateTimeFormatter? withOffsetParsed()
```

Returns: `DateTimeFormatter?`

#### `withZone`

```norm
DateTimeFormatter? withZone(DateTimeZone? arg0)
```

Parameters:

- `arg0`: `DateTimeZone?`

Returns: `DateTimeFormatter?`

#### `withZoneUTC`

```norm
DateTimeFormatter? withZoneUTC()
```

Returns: `DateTimeFormatter?`

## `joda.time`

Source: `DateTimeZone.norm`

### `DateTimeZone`

```norm
class DateTimeZone implements Serializable
```

#### `DateTimeZone`

```norm
DateTimeZone(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `getID`

```norm
String? getID()
```

Returns: `String?`

#### `getOffset`

```norm
Integer getOffset(Long arg0)
```

Parameters:

- `arg0`: `Long`

Returns: `Integer`

#### `isFixed`

```norm
Boolean isFixed()
```

Returns: `Boolean`

#### `toString`

```norm
String? toString()
```

Returns: `String?`

### `dateTimeZoneFieldGetUtc`

```norm
DateTimeZone? dateTimeZoneFieldGetUtc()
```

Returns: `DateTimeZone?`

### `dateTimeZoneForID`

```norm
DateTimeZone? dateTimeZoneForID(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `DateTimeZone?`

### `dateTimeZoneForOffsetHours`

```norm
DateTimeZone? dateTimeZoneForOffsetHours(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `DateTimeZone?`

### `dateTimeZoneGetDefault`

```norm
DateTimeZone? dateTimeZoneGetDefault()
```

Returns: `DateTimeZone?`

## `joda.time`

Source: `Days.norm`

### `Days`

```norm
class Days extends BaseSingleFieldPeriod implements ReadablePeriod, Comparable<BaseSingleFieldPeriod>, Serializable
```

#### `Days`

```norm
Days(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `dividedBy`

```norm
Days? dividedBy(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Days?`

#### `getDays`

```norm
Integer getDays()
```

Returns: `Integer`

#### `isGreaterThan`

```norm
Boolean isGreaterThan(Days? arg0)
```

Parameters:

- `arg0`: `Days?`

Returns: `Boolean`

#### `isLessThan`

```norm
Boolean isLessThan(Days? arg0)
```

Parameters:

- `arg0`: `Days?`

Returns: `Boolean`

#### `minus`

```norm
Days? minus(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Days?`

#### `minus`

```norm
Days? minus(Days? arg0)
```

Parameters:

- `arg0`: `Days?`

Returns: `Days?`

#### `multipliedBy`

```norm
Days? multipliedBy(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Days?`

#### `negated`

```norm
Days? negated()
```

Returns: `Days?`

#### `plus`

```norm
Days? plus(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Days?`

#### `plus`

```norm
Days? plus(Days? arg0)
```

Parameters:

- `arg0`: `Days?`

Returns: `Days?`

#### `toStandardDuration`

```norm
Duration? toStandardDuration()
```

Returns: `Duration?`

#### `toString`

```norm
String? toString()
```

Returns: `String?`

### `daysFieldGetOne`

```norm
Days? daysFieldGetOne()
```

Returns: `Days?`

### `daysFieldGetZero`

```norm
Days? daysFieldGetZero()
```

Returns: `Days?`

### `daysDays`

```norm
Days? daysDays(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Days?`

### `daysDaysBetween`

```norm
Days? daysDaysBetween(ReadablePartial? arg0, ReadablePartial? arg1)
```

Parameters:

- `arg0`: `ReadablePartial?`
- `arg1`: `ReadablePartial?`

Returns: `Days?`

### `daysDaysIn`

```norm
Days? daysDaysIn(ReadableInterval? arg0)
```

Parameters:

- `arg0`: `ReadableInterval?`

Returns: `Days?`

### `daysParseDays`

```norm
Days? daysParseDays(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Days?`

### `daysStandardDaysIn`

```norm
Days? daysStandardDaysIn(ReadablePeriod? arg0)
```

Parameters:

- `arg0`: `ReadablePeriod?`

Returns: `Days?`

## `joda.time`

Source: `Duration.norm`

### `Duration`

```norm
class Duration extends BaseDuration implements ReadableDuration, Serializable
```

#### `Duration`

```norm
Duration(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `abs`

```norm
Duration? abs()
```

Returns: `Duration?`

#### `dividedBy`

```norm
Duration? dividedBy(Long arg0)
```

Parameters:

- `arg0`: `Long`

Returns: `Duration?`

#### `getMillis`

```norm
Long getMillis()
```

Returns: `Long`

#### `getStandardDays`

```norm
Long getStandardDays()
```

Returns: `Long`

#### `getStandardHours`

```norm
Long getStandardHours()
```

Returns: `Long`

#### `getStandardMinutes`

```norm
Long getStandardMinutes()
```

Returns: `Long`

#### `getStandardSeconds`

```norm
Long getStandardSeconds()
```

Returns: `Long`

#### `minus`

```norm
Duration? minus(Long arg0)
```

Parameters:

- `arg0`: `Long`

Returns: `Duration?`

#### `multipliedBy`

```norm
Duration? multipliedBy(Long arg0)
```

Parameters:

- `arg0`: `Long`

Returns: `Duration?`

#### `negated`

```norm
Duration? negated()
```

Returns: `Duration?`

#### `plus`

```norm
Duration? plus(Long arg0)
```

Parameters:

- `arg0`: `Long`

Returns: `Duration?`

### `durationFieldGetZero`

```norm
Duration? durationFieldGetZero()
```

Returns: `Duration?`

### `durationNew`

```norm
Duration durationNew(Long arg0)
```

Parameters:

- `arg0`: `Long`

Returns: `Duration`

### `durationMillis`

```norm
Duration? durationMillis(Long arg0)
```

Parameters:

- `arg0`: `Long`

Returns: `Duration?`

### `durationParse`

```norm
Duration? durationParse(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Duration?`

### `durationStandardDays`

```norm
Duration? durationStandardDays(Long arg0)
```

Parameters:

- `arg0`: `Long`

Returns: `Duration?`

### `durationStandardHours`

```norm
Duration? durationStandardHours(Long arg0)
```

Parameters:

- `arg0`: `Long`

Returns: `Duration?`

### `durationStandardMinutes`

```norm
Duration? durationStandardMinutes(Long arg0)
```

Parameters:

- `arg0`: `Long`

Returns: `Duration?`

### `durationStandardSeconds`

```norm
Duration? durationStandardSeconds(Long arg0)
```

Parameters:

- `arg0`: `Long`

Returns: `Duration?`

## `joda.time`

Source: `ISODateTimeFormat.norm`

### `ISODateTimeFormat`

```norm
class ISODateTimeFormat
```

#### `ISODateTimeFormat`

```norm
ISODateTimeFormat(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

### `isoDateTimeFormatBasicDate`

```norm
DateTimeFormatter? isoDateTimeFormatBasicDate()
```

Returns: `DateTimeFormatter?`

### `isoDateTimeFormatBasicDateTime`

```norm
DateTimeFormatter? isoDateTimeFormatBasicDateTime()
```

Returns: `DateTimeFormatter?`

### `isoDateTimeFormatDate`

```norm
DateTimeFormatter? isoDateTimeFormatDate()
```

Returns: `DateTimeFormatter?`

### `isoDateTimeFormatDateOptionalTimeParser`

```norm
DateTimeFormatter? isoDateTimeFormatDateOptionalTimeParser()
```

Returns: `DateTimeFormatter?`

### `isoDateTimeFormatDateParser`

```norm
DateTimeFormatter? isoDateTimeFormatDateParser()
```

Returns: `DateTimeFormatter?`

### `isoDateTimeFormatDateTime`

```norm
DateTimeFormatter? isoDateTimeFormatDateTime()
```

Returns: `DateTimeFormatter?`

### `isoDateTimeFormatDateTimeNoMillis`

```norm
DateTimeFormatter? isoDateTimeFormatDateTimeNoMillis()
```

Returns: `DateTimeFormatter?`

### `isoDateTimeFormatDateTimeParser`

```norm
DateTimeFormatter? isoDateTimeFormatDateTimeParser()
```

Returns: `DateTimeFormatter?`

### `isoDateTimeFormatLocalDateOptionalTimeParser`

```norm
DateTimeFormatter? isoDateTimeFormatLocalDateOptionalTimeParser()
```

Returns: `DateTimeFormatter?`

### `isoDateTimeFormatLocalDateParser`

```norm
DateTimeFormatter? isoDateTimeFormatLocalDateParser()
```

Returns: `DateTimeFormatter?`

### `isoDateTimeFormatLocalTimeParser`

```norm
DateTimeFormatter? isoDateTimeFormatLocalTimeParser()
```

Returns: `DateTimeFormatter?`

### `isoDateTimeFormatTime`

```norm
DateTimeFormatter? isoDateTimeFormatTime()
```

Returns: `DateTimeFormatter?`

### `isoDateTimeFormatTimeNoMillis`

```norm
DateTimeFormatter? isoDateTimeFormatTimeNoMillis()
```

Returns: `DateTimeFormatter?`

### `isoDateTimeFormatTimeParser`

```norm
DateTimeFormatter? isoDateTimeFormatTimeParser()
```

Returns: `DateTimeFormatter?`

## `joda.time`

Source: `Instant.norm`

### `Instant`

```norm
class Instant extends AbstractInstant implements ReadableInstant, Serializable
```

#### `Instant`

```norm
Instant(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `getMillis`

```norm
Long getMillis()
```

Returns: `Long`

#### `minus`

```norm
Instant? minus(Long arg0)
```

Parameters:

- `arg0`: `Long`

Returns: `Instant?`

#### `plus`

```norm
Instant? plus(Long arg0)
```

Parameters:

- `arg0`: `Long`

Returns: `Instant?`

#### `toDateTime`

```norm
DateTime? toDateTime()
```

Returns: `DateTime?`

#### `toDateTime`

```norm
DateTime? toDateTime(Chronology? arg0)
```

Parameters:

- `arg0`: `Chronology?`

Returns: `DateTime?`

#### `toDateTime`

```norm
DateTime? toDateTime(DateTimeZone? arg0)
```

Parameters:

- `arg0`: `DateTimeZone?`

Returns: `DateTime?`

#### `toString`

```norm
String? toString()
```

Returns: `String?`

#### `withMillis`

```norm
Instant? withMillis(Long arg0)
```

Parameters:

- `arg0`: `Long`

Returns: `Instant?`

### `instantFieldGetEpoch`

```norm
Instant? instantFieldGetEpoch()
```

Returns: `Instant?`

### `instantNew`

```norm
Instant instantNew(Long arg0)
```

Parameters:

- `arg0`: `Long`

Returns: `Instant`

### `instantNow`

```norm
Instant? instantNow()
```

Returns: `Instant?`

### `instantOfEpochMilli`

```norm
Instant? instantOfEpochMilli(Long arg0)
```

Parameters:

- `arg0`: `Long`

Returns: `Instant?`

### `instantOfEpochSecond`

```norm
Instant? instantOfEpochSecond(Long arg0)
```

Parameters:

- `arg0`: `Long`

Returns: `Instant?`

### `instantParse`

```norm
Instant? instantParse(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Instant?`

## `joda.time`

Source: `Interval.norm`

### `Interval`

```norm
class Interval extends BaseInterval implements ReadableInterval, Serializable
```

#### `Interval`

```norm
Interval(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `abuts`

```norm
Boolean abuts(ReadableInterval? arg0)
```

Parameters:

- `arg0`: `ReadableInterval?`

Returns: `Boolean`

#### `contains`

```norm
Boolean contains(Long arg0)
```

Parameters:

- `arg0`: `Long`

Returns: `Boolean`

#### `gap`

```norm
Interval? gap(ReadableInterval? arg0)
```

Parameters:

- `arg0`: `ReadableInterval?`

Returns: `Interval?`

#### `getEnd`

```norm
DateTime? getEnd()
```

Returns: `DateTime?`

#### `getStart`

```norm
DateTime? getStart()
```

Returns: `DateTime?`

#### `overlap`

```norm
Interval? overlap(ReadableInterval? arg0)
```

Parameters:

- `arg0`: `ReadableInterval?`

Returns: `Interval?`

#### `overlaps`

```norm
Boolean overlaps(ReadableInterval? arg0)
```

Parameters:

- `arg0`: `ReadableInterval?`

Returns: `Boolean`

#### `toDuration`

```norm
Duration? toDuration()
```

Returns: `Duration?`

#### `toDurationMillis`

```norm
Long toDurationMillis()
```

Returns: `Long`

#### `toString`

```norm
String? toString()
```

Returns: `String?`

#### `withEndMillis`

```norm
Interval? withEndMillis(Long arg0)
```

Parameters:

- `arg0`: `Long`

Returns: `Interval?`

#### `withStartMillis`

```norm
Interval? withStartMillis(Long arg0)
```

Parameters:

- `arg0`: `Long`

Returns: `Interval?`

### `intervalNew`

```norm
Interval intervalNew(Long arg0, Long arg1)
```

Parameters:

- `arg0`: `Long`
- `arg1`: `Long`

Returns: `Interval`

### `intervalParse`

```norm
Interval? intervalParse(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Interval?`

## `joda.time`

Source: `LocalDate.norm`

### `LocalDate`

```norm
class LocalDate extends BaseLocal implements ReadablePartial, Serializable, Comparable<ReadablePartial>
```

#### `LocalDate`

```norm
LocalDate(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `getDayOfMonth`

```norm
Integer getDayOfMonth()
```

Returns: `Integer`

#### `getDayOfWeek`

```norm
Integer getDayOfWeek()
```

Returns: `Integer`

#### `getDayOfYear`

```norm
Integer getDayOfYear()
```

Returns: `Integer`

#### `getMonthOfYear`

```norm
Integer getMonthOfYear()
```

Returns: `Integer`

#### `getYear`

```norm
Integer getYear()
```

Returns: `Integer`

#### `minusDays`

```norm
LocalDate? minusDays(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `LocalDate?`

#### `minusMonths`

```norm
LocalDate? minusMonths(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `LocalDate?`

#### `minusWeeks`

```norm
LocalDate? minusWeeks(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `LocalDate?`

#### `minusYears`

```norm
LocalDate? minusYears(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `LocalDate?`

#### `plusDays`

```norm
LocalDate? plusDays(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `LocalDate?`

#### `plusMonths`

```norm
LocalDate? plusMonths(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `LocalDate?`

#### `plusWeeks`

```norm
LocalDate? plusWeeks(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `LocalDate?`

#### `plusYears`

```norm
LocalDate? plusYears(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `LocalDate?`

#### `toDateTimeAtStartOfDay`

```norm
DateTime? toDateTimeAtStartOfDay()
```

Returns: `DateTime?`

#### `toDateTimeAtStartOfDay`

```norm
DateTime? toDateTimeAtStartOfDay(DateTimeZone? arg0)
```

Parameters:

- `arg0`: `DateTimeZone?`

Returns: `DateTime?`

#### `toInterval`

```norm
Interval? toInterval()
```

Returns: `Interval?`

#### `toInterval`

```norm
Interval? toInterval(DateTimeZone? arg0)
```

Parameters:

- `arg0`: `DateTimeZone?`

Returns: `Interval?`

#### `toString`

```norm
String? toString()
```

Returns: `String?`

#### `withDayOfMonth`

```norm
LocalDate? withDayOfMonth(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `LocalDate?`

#### `withMonthOfYear`

```norm
LocalDate? withMonthOfYear(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `LocalDate?`

#### `withYear`

```norm
LocalDate? withYear(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `LocalDate?`

### `localDateNew`

```norm
LocalDate localDateNew(Integer arg0, Integer arg1, Integer arg2)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `Integer`
- `arg2`: `Integer`

Returns: `LocalDate`

### `localDateNow`

```norm
LocalDate? localDateNow()
```

Returns: `LocalDate?`

### `localDateNow`

```norm
LocalDate? localDateNow(Chronology? arg0)
```

Parameters:

- `arg0`: `Chronology?`

Returns: `LocalDate?`

### `localDateNow`

```norm
LocalDate? localDateNow(DateTimeZone? arg0)
```

Parameters:

- `arg0`: `DateTimeZone?`

Returns: `LocalDate?`

### `localDateParse`

```norm
LocalDate? localDateParse(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `LocalDate?`

## `joda.time`

Source: `LocalDateTime.norm`

### `LocalDateTime`

```norm
class LocalDateTime extends BaseLocal implements ReadablePartial, Serializable, Comparable<ReadablePartial>
```

#### `LocalDateTime`

```norm
LocalDateTime(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `getDayOfMonth`

```norm
Integer getDayOfMonth()
```

Returns: `Integer`

#### `getDayOfWeek`

```norm
Integer getDayOfWeek()
```

Returns: `Integer`

#### `getHourOfDay`

```norm
Integer getHourOfDay()
```

Returns: `Integer`

#### `getMinuteOfHour`

```norm
Integer getMinuteOfHour()
```

Returns: `Integer`

#### `getMonthOfYear`

```norm
Integer getMonthOfYear()
```

Returns: `Integer`

#### `getSecondOfMinute`

```norm
Integer getSecondOfMinute()
```

Returns: `Integer`

#### `getYear`

```norm
Integer getYear()
```

Returns: `Integer`

#### `minusDays`

```norm
LocalDateTime? minusDays(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `LocalDateTime?`

#### `minusHours`

```norm
LocalDateTime? minusHours(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `LocalDateTime?`

#### `minusMinutes`

```norm
LocalDateTime? minusMinutes(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `LocalDateTime?`

#### `minusMonths`

```norm
LocalDateTime? minusMonths(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `LocalDateTime?`

#### `minusSeconds`

```norm
LocalDateTime? minusSeconds(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `LocalDateTime?`

#### `minusWeeks`

```norm
LocalDateTime? minusWeeks(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `LocalDateTime?`

#### `minusYears`

```norm
LocalDateTime? minusYears(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `LocalDateTime?`

#### `plusDays`

```norm
LocalDateTime? plusDays(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `LocalDateTime?`

#### `plusHours`

```norm
LocalDateTime? plusHours(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `LocalDateTime?`

#### `plusMinutes`

```norm
LocalDateTime? plusMinutes(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `LocalDateTime?`

#### `plusMonths`

```norm
LocalDateTime? plusMonths(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `LocalDateTime?`

#### `plusSeconds`

```norm
LocalDateTime? plusSeconds(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `LocalDateTime?`

#### `plusWeeks`

```norm
LocalDateTime? plusWeeks(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `LocalDateTime?`

#### `plusYears`

```norm
LocalDateTime? plusYears(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `LocalDateTime?`

#### `toDateTime`

```norm
DateTime? toDateTime()
```

Returns: `DateTime?`

#### `toDateTime`

```norm
DateTime? toDateTime(DateTimeZone? arg0)
```

Parameters:

- `arg0`: `DateTimeZone?`

Returns: `DateTime?`

#### `toDateTime`

```norm
DateTime? toDateTime(ReadableInstant? arg0)
```

Parameters:

- `arg0`: `ReadableInstant?`

Returns: `DateTime?`

#### `toLocalDate`

```norm
LocalDate? toLocalDate()
```

Returns: `LocalDate?`

#### `toLocalTime`

```norm
LocalTime? toLocalTime()
```

Returns: `LocalTime?`

#### `toString`

```norm
String? toString()
```

Returns: `String?`

#### `withDate`

```norm
LocalDateTime? withDate(Integer arg0, Integer arg1, Integer arg2)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `Integer`
- `arg2`: `Integer`

Returns: `LocalDateTime?`

#### `withTime`

```norm
LocalDateTime? withTime(Integer arg0, Integer arg1, Integer arg2, Integer arg3)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `Integer`
- `arg2`: `Integer`
- `arg3`: `Integer`

Returns: `LocalDateTime?`

### `localDateTimeNew`

```norm
LocalDateTime localDateTimeNew(Integer arg0, Integer arg1, Integer arg2, Integer arg3, Integer arg4)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `Integer`
- `arg2`: `Integer`
- `arg3`: `Integer`
- `arg4`: `Integer`

Returns: `LocalDateTime`

### `localDateTimeNow`

```norm
LocalDateTime? localDateTimeNow()
```

Returns: `LocalDateTime?`

### `localDateTimeNow`

```norm
LocalDateTime? localDateTimeNow(Chronology? arg0)
```

Parameters:

- `arg0`: `Chronology?`

Returns: `LocalDateTime?`

### `localDateTimeNow`

```norm
LocalDateTime? localDateTimeNow(DateTimeZone? arg0)
```

Parameters:

- `arg0`: `DateTimeZone?`

Returns: `LocalDateTime?`

### `localDateTimeParse`

```norm
LocalDateTime? localDateTimeParse(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `LocalDateTime?`

## `joda.time`

Source: `LocalTime.norm`

### `LocalTime`

```norm
class LocalTime extends BaseLocal implements ReadablePartial, Serializable, Comparable<ReadablePartial>
```

#### `LocalTime`

```norm
LocalTime(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `getHourOfDay`

```norm
Integer getHourOfDay()
```

Returns: `Integer`

#### `getMillisOfDay`

```norm
Integer getMillisOfDay()
```

Returns: `Integer`

#### `getMinuteOfHour`

```norm
Integer getMinuteOfHour()
```

Returns: `Integer`

#### `getSecondOfMinute`

```norm
Integer getSecondOfMinute()
```

Returns: `Integer`

#### `minusHours`

```norm
LocalTime? minusHours(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `LocalTime?`

#### `minusMinutes`

```norm
LocalTime? minusMinutes(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `LocalTime?`

#### `minusSeconds`

```norm
LocalTime? minusSeconds(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `LocalTime?`

#### `plusHours`

```norm
LocalTime? plusHours(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `LocalTime?`

#### `plusMinutes`

```norm
LocalTime? plusMinutes(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `LocalTime?`

#### `plusSeconds`

```norm
LocalTime? plusSeconds(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `LocalTime?`

#### `toDateTimeToday`

```norm
DateTime? toDateTimeToday()
```

Returns: `DateTime?`

#### `toDateTimeToday`

```norm
DateTime? toDateTimeToday(DateTimeZone? arg0)
```

Parameters:

- `arg0`: `DateTimeZone?`

Returns: `DateTime?`

#### `toString`

```norm
String? toString()
```

Returns: `String?`

#### `withHourOfDay`

```norm
LocalTime? withHourOfDay(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `LocalTime?`

#### `withMinuteOfHour`

```norm
LocalTime? withMinuteOfHour(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `LocalTime?`

#### `withSecondOfMinute`

```norm
LocalTime? withSecondOfMinute(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `LocalTime?`

### `localTimeFieldGetMidnight`

```norm
LocalTime? localTimeFieldGetMidnight()
```

Returns: `LocalTime?`

### `localTimeNew`

```norm
LocalTime localTimeNew(Integer arg0, Integer arg1)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `Integer`

Returns: `LocalTime`

### `localTimeFromMillisOfDay`

```norm
LocalTime? localTimeFromMillisOfDay(Long arg0)
```

Parameters:

- `arg0`: `Long`

Returns: `LocalTime?`

### `localTimeFromMillisOfDay`

```norm
LocalTime? localTimeFromMillisOfDay(Long arg0, Chronology? arg1)
```

Parameters:

- `arg0`: `Long`
- `arg1`: `Chronology?`

Returns: `LocalTime?`

### `localTimeNow`

```norm
LocalTime? localTimeNow()
```

Returns: `LocalTime?`

### `localTimeNow`

```norm
LocalTime? localTimeNow(Chronology? arg0)
```

Parameters:

- `arg0`: `Chronology?`

Returns: `LocalTime?`

### `localTimeNow`

```norm
LocalTime? localTimeNow(DateTimeZone? arg0)
```

Parameters:

- `arg0`: `DateTimeZone?`

Returns: `LocalTime?`

### `localTimeParse`

```norm
LocalTime? localTimeParse(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `LocalTime?`

## `joda.time`

Source: `Months.norm`

### `Months`

```norm
class Months extends BaseSingleFieldPeriod implements ReadablePeriod, Comparable<BaseSingleFieldPeriod>, Serializable
```

#### `Months`

```norm
Months(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `dividedBy`

```norm
Months? dividedBy(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Months?`

#### `getMonths`

```norm
Integer getMonths()
```

Returns: `Integer`

#### `isGreaterThan`

```norm
Boolean isGreaterThan(Months? arg0)
```

Parameters:

- `arg0`: `Months?`

Returns: `Boolean`

#### `isLessThan`

```norm
Boolean isLessThan(Months? arg0)
```

Parameters:

- `arg0`: `Months?`

Returns: `Boolean`

#### `minus`

```norm
Months? minus(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Months?`

#### `minus`

```norm
Months? minus(Months? arg0)
```

Parameters:

- `arg0`: `Months?`

Returns: `Months?`

#### `multipliedBy`

```norm
Months? multipliedBy(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Months?`

#### `negated`

```norm
Months? negated()
```

Returns: `Months?`

#### `plus`

```norm
Months? plus(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Months?`

#### `plus`

```norm
Months? plus(Months? arg0)
```

Parameters:

- `arg0`: `Months?`

Returns: `Months?`

#### `toString`

```norm
String? toString()
```

Returns: `String?`

### `monthsFieldGetOne`

```norm
Months? monthsFieldGetOne()
```

Returns: `Months?`

### `monthsFieldGetZero`

```norm
Months? monthsFieldGetZero()
```

Returns: `Months?`

### `monthsMonths`

```norm
Months? monthsMonths(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Months?`

### `monthsMonthsBetween`

```norm
Months? monthsMonthsBetween(ReadablePartial? arg0, ReadablePartial? arg1)
```

Parameters:

- `arg0`: `ReadablePartial?`
- `arg1`: `ReadablePartial?`

Returns: `Months?`

### `monthsMonthsIn`

```norm
Months? monthsMonthsIn(ReadableInterval? arg0)
```

Parameters:

- `arg0`: `ReadableInterval?`

Returns: `Months?`

### `monthsParseMonths`

```norm
Months? monthsParseMonths(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Months?`

## `joda.time`

Source: `Period.norm`

### `Period`

```norm
class Period extends BasePeriod implements ReadablePeriod, Serializable
```

#### `Period`

```norm
Period(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `getDays`

```norm
Integer getDays()
```

Returns: `Integer`

#### `getHours`

```norm
Integer getHours()
```

Returns: `Integer`

#### `getMillis`

```norm
Integer getMillis()
```

Returns: `Integer`

#### `getMinutes`

```norm
Integer getMinutes()
```

Returns: `Integer`

#### `getMonths`

```norm
Integer getMonths()
```

Returns: `Integer`

#### `getSeconds`

```norm
Integer getSeconds()
```

Returns: `Integer`

#### `getWeeks`

```norm
Integer getWeeks()
```

Returns: `Integer`

#### `getYears`

```norm
Integer getYears()
```

Returns: `Integer`

#### `multipliedBy`

```norm
Period? multipliedBy(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Period?`

#### `negated`

```norm
Period? negated()
```

Returns: `Period?`

#### `normalizedStandard`

```norm
Period? normalizedStandard()
```

Returns: `Period?`

#### `normalizedStandard`

```norm
Period? normalizedStandard(PeriodType? arg0)
```

Parameters:

- `arg0`: `PeriodType?`

Returns: `Period?`

#### `plusDays`

```norm
Period? plusDays(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Period?`

#### `plusHours`

```norm
Period? plusHours(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Period?`

#### `plusMillis`

```norm
Period? plusMillis(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Period?`

#### `plusMinutes`

```norm
Period? plusMinutes(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Period?`

#### `plusMonths`

```norm
Period? plusMonths(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Period?`

#### `plusSeconds`

```norm
Period? plusSeconds(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Period?`

#### `plusWeeks`

```norm
Period? plusWeeks(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Period?`

#### `plusYears`

```norm
Period? plusYears(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Period?`

#### `toStandardDuration`

```norm
Duration? toStandardDuration()
```

Returns: `Duration?`

### `periodFieldGetZero`

```norm
Period? periodFieldGetZero()
```

Returns: `Period?`

### `periodNew`

```norm
Period periodNew()
```

Returns: `Period`

### `periodDays`

```norm
Period? periodDays(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Period?`

### `periodHours`

```norm
Period? periodHours(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Period?`

### `periodMillis`

```norm
Period? periodMillis(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Period?`

### `periodMinutes`

```norm
Period? periodMinutes(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Period?`

### `periodMonths`

```norm
Period? periodMonths(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Period?`

### `periodParse`

```norm
Period? periodParse(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Period?`

### `periodSeconds`

```norm
Period? periodSeconds(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Period?`

### `periodWeeks`

```norm
Period? periodWeeks(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Period?`

### `periodYears`

```norm
Period? periodYears(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Period?`

## `joda.time`

Source: `PeriodType.norm`

### `PeriodType`

```norm
class PeriodType implements Serializable
```

#### `PeriodType`

```norm
PeriodType(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `joda.time`

Source: `ReadableDateTime.norm`

### `ReadableDateTime`

```norm
interface ReadableDateTime extends ReadableInstant
```

## `joda.time`

Source: `ReadableDuration.norm`

### `ReadableDuration`

```norm
interface ReadableDuration extends Comparable<ReadableDuration>
```

## `joda.time`

Source: `ReadableInstant.norm`

### `ReadableInstant`

```norm
interface ReadableInstant extends Comparable<ReadableInstant>
```

## `joda.time`

Source: `ReadableInterval.norm`

### `ReadableInterval`

```norm
interface ReadableInterval
```

## `joda.time`

Source: `ReadablePartial.norm`

### `ReadablePartial`

```norm
interface ReadablePartial extends Comparable<ReadablePartial>
```

## `joda.time`

Source: `ReadablePeriod.norm`

### `ReadablePeriod`

```norm
interface ReadablePeriod
```

## `joda.time`

Source: `Years.norm`

### `Years`

```norm
class Years extends BaseSingleFieldPeriod implements ReadablePeriod, Comparable<BaseSingleFieldPeriod>, Serializable
```

#### `Years`

```norm
Years(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `dividedBy`

```norm
Years? dividedBy(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Years?`

#### `getYears`

```norm
Integer getYears()
```

Returns: `Integer`

#### `isGreaterThan`

```norm
Boolean isGreaterThan(Years? arg0)
```

Parameters:

- `arg0`: `Years?`

Returns: `Boolean`

#### `isLessThan`

```norm
Boolean isLessThan(Years? arg0)
```

Parameters:

- `arg0`: `Years?`

Returns: `Boolean`

#### `minus`

```norm
Years? minus(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Years?`

#### `minus`

```norm
Years? minus(Years? arg0)
```

Parameters:

- `arg0`: `Years?`

Returns: `Years?`

#### `multipliedBy`

```norm
Years? multipliedBy(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Years?`

#### `negated`

```norm
Years? negated()
```

Returns: `Years?`

#### `plus`

```norm
Years? plus(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Years?`

#### `plus`

```norm
Years? plus(Years? arg0)
```

Parameters:

- `arg0`: `Years?`

Returns: `Years?`

#### `toString`

```norm
String? toString()
```

Returns: `String?`

### `yearsFieldGetOne`

```norm
Years? yearsFieldGetOne()
```

Returns: `Years?`

### `yearsFieldGetZero`

```norm
Years? yearsFieldGetZero()
```

Returns: `Years?`

### `yearsParseYears`

```norm
Years? yearsParseYears(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Years?`

### `yearsYears`

```norm
Years? yearsYears(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Years?`

### `yearsYearsBetween`

```norm
Years? yearsYearsBetween(ReadablePartial? arg0, ReadablePartial? arg1)
```

Parameters:

- `arg0`: `ReadablePartial?`
- `arg1`: `ReadablePartial?`

Returns: `Years?`

### `yearsYearsIn`

```norm
Years? yearsYearsIn(ReadableInterval? arg0)
```

Parameters:

- `arg0`: `ReadableInterval?`

Returns: `Years?`

## `joda.time.base`

Source: `base/AbstractDateTime.norm`

### `AbstractDateTime`

```norm
class AbstractDateTime extends AbstractInstant implements ReadableDateTime, ReadableInstant
```

#### `AbstractDateTime`

```norm
AbstractDateTime(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `joda.time.base`

Source: `base/AbstractDuration.norm`

### `AbstractDuration`

```norm
class AbstractDuration implements ReadableDuration
```

#### `AbstractDuration`

```norm
AbstractDuration(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `joda.time.base`

Source: `base/AbstractInstant.norm`

### `AbstractInstant`

```norm
class AbstractInstant implements ReadableInstant
```

#### `AbstractInstant`

```norm
AbstractInstant(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `joda.time.base`

Source: `base/AbstractInterval.norm`

### `AbstractInterval`

```norm
class AbstractInterval implements ReadableInterval
```

#### `AbstractInterval`

```norm
AbstractInterval(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `joda.time.base`

Source: `base/AbstractPartial.norm`

### `AbstractPartial`

```norm
class AbstractPartial implements ReadablePartial, Comparable<ReadablePartial>
```

#### `AbstractPartial`

```norm
AbstractPartial(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `joda.time.base`

Source: `base/AbstractPeriod.norm`

### `AbstractPeriod`

```norm
class AbstractPeriod implements ReadablePeriod
```

#### `AbstractPeriod`

```norm
AbstractPeriod(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `joda.time.base`

Source: `base/BaseDateTime.norm`

### `BaseDateTime`

```norm
class BaseDateTime extends AbstractDateTime implements ReadableDateTime, Serializable, ReadableInstant
```

#### `BaseDateTime`

```norm
BaseDateTime(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `joda.time.base`

Source: `base/BaseDuration.norm`

### `BaseDuration`

```norm
class BaseDuration extends AbstractDuration implements ReadableDuration, Serializable
```

#### `BaseDuration`

```norm
BaseDuration(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `joda.time.base`

Source: `base/BaseInterval.norm`

### `BaseInterval`

```norm
class BaseInterval extends AbstractInterval implements ReadableInterval, Serializable
```

#### `BaseInterval`

```norm
BaseInterval(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `joda.time.base`

Source: `base/BaseLocal.norm`

### `BaseLocal`

```norm
class BaseLocal extends AbstractPartial implements ReadablePartial, Comparable<ReadablePartial>
```

#### `BaseLocal`

```norm
BaseLocal(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `joda.time.base`

Source: `base/BasePeriod.norm`

### `BasePeriod`

```norm
class BasePeriod extends AbstractPeriod implements ReadablePeriod, Serializable
```

#### `BasePeriod`

```norm
BasePeriod(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `joda.time.base`

Source: `base/BaseSingleFieldPeriod.norm`

### `BaseSingleFieldPeriod`

```norm
class BaseSingleFieldPeriod implements ReadablePeriod, Comparable<BaseSingleFieldPeriod>, Serializable
```

#### `BaseSingleFieldPeriod`

```norm
BaseSingleFieldPeriod(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

