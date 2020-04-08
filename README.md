# How to customize the Schedule view label format in Xamarin.Forms (SfSchedule) ?

You can customize the schedule view label by using [TimeFormat](https://help.syncfusion.com/cr/cref_files/xamarin/Syncfusion.SfSchedule.XForms~Syncfusion.SfSchedule.XForms.DayLabelSettings~TimeFormat.html?) property in each ScheduleView in Xamarin.Forms [SfSchedule](https://help.syncfusion.com/xamarin/scheduler/overview?).

You can also refer the following article.

https://www.syncfusion.com/kb/11313/how-to-customize-the-schedule-view-label-format-in-xamarin-forms-sfschedule

**DayView**

Customize the DayView label by setting TimeFormat property in [DayLabelSettings](https://help.syncfusion.com/cr/cref_files/xamarin/Syncfusion.SfSchedule.XForms~Syncfusion.SfSchedule.XForms.DayViewSettings~DayLabelSettings.html?).

``` xml
<schedule:SfSchedule.DayViewSettings>
                    <schedule:DayViewSettings>
                        <schedule:DayViewSettings.DayLabelSettings>
                            <schedule:DayLabelSettings TimeFormat="hh:mm"/>
                        </schedule:DayViewSettings.DayLabelSettings>
                    </schedule:DayViewSettings>
</schedule:SfSchedule.DayViewSettings>
```

**WeekView**

Customize the WeekView label by setting TimeFormat property in [WeekLabelSettings](https://help.syncfusion.com/cr/cref_files/xamarin/Syncfusion.SfSchedule.XForms~Syncfusion.SfSchedule.XForms.WeekViewSettings~WeekLabelSettings.html?). 
``` xml
<schedule:SfSchedule.WeekViewSettings>
                    <schedule:WeekViewSettings>
                        <schedule:WeekViewSettings.WeekLabelSettings>
                            <schedule:WeekLabelSettings TimeFormat="hh:mm"/>
                        </schedule:WeekViewSettings.WeekLabelSettings>
                    </schedule:WeekViewSettings>
</schedule:SfSchedule.WeekViewSettings>
```

**WorkWeekView**

Customize the WorkWeekView label by setting TimeFormat property in [WorkWeekLabelSettings](https://help.syncfusion.com/cr/cref_files/xamarin/Syncfusion.SfSchedule.XForms~Syncfusion.SfSchedule.XForms.WorkWeekViewSettings~WorkWeekLabelSettings.html?).

``` xml
<schedule:SfSchedule.WorkWeekViewSettings>
                    <schedule:WorkWeekViewSettings>
                        <schedule:WorkWeekViewSettings.WorkWeekLabelSettings>
                            <schedule:WorkWeekLabelSettings TimeFormat="hh:mm"/>
                        </schedule:WorkWeekViewSettings.WorkWeekLabelSettings>
                    </schedule:WorkWeekViewSettings>
</schedule:SfSchedule.WorkWeekViewSettings>
```

**TimelineView**

Customize the TimelineView label by setting TimeFormat property in  of [LabelSettings](https://help.syncfusion.com/cr/cref_files/xamarin/Syncfusion.SfSchedule.XForms~Syncfusion.SfSchedule.XForms.TimelineViewSettings~LabelSettings.html?).

``` xml
<schedule:SfSchedule.TimelineViewSettings>
                    <schedule:TimelineViewSettings>
                        <schedule:TimelineViewSettings.LabelSettings>
                            <schedule:TimelineLabelSettings TimeFormat="hh:mm"/>
                        </schedule:TimelineViewSettings.LabelSettings>
                    </schedule:TimelineViewSettings>
</schedule:SfSchedule.TimelineViewSettings>
```
