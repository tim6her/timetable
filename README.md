# Timetable

This a *LaTeX* template implementing a simple schedule.

![Example][imgs/Timetable.png]

## Usage

Just add your calendar entries in the `timetable` environment
like this, where the arguments to the environment denote the
start and end time of your workday.

```latex
\begin{timetable}{8}{17}
	\calentry{1}{8.30}{9.45}{Dentist}{Dentist's Place}
\end{timetable}
```

The syntax of the `\calentry` and `\shortcalentry` are as follows.

```latex
\calentry[CALENDARSTYLE]{DAYOFWEEK}{STARTTIME}{ENDTIME}{SUBJECT}{PLACE}
```

`\shortcalentry` displays appointments in a more compact form.

Names of the weekdays adapt dynamically to your language option
of `babel`.
