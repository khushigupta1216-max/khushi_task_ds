# Student Performance Predictor — Linear Regression Demo

## Files

- `app.py` — Streamlit application
- `linear_regression_final.joblib` — trained Linear Regression pipeline
- `requirements.txt` — Python dependencies

## Run locally

```bash
pip install -r requirements.txt
streamlit run app.py
```

The model file must be in the same directory as `app.py`.

## Model input

The application uses the exact enhanced Linear Regression input schema:

- Age
- Gender
- AttendancePct
- StudyHoursPerWeek
- PreviousGrade
- AssignmentMarks
- InternalAssessmentMarks
- OnlineClasses
- ExtracurricularActivities
- ParentalSupport
- AttendanceStudyInteraction

`AttendanceStudyInteraction` is computed by the app as:

`AttendancePct × StudyHoursPerWeek`

The application does not use `FinalExamMarks` as an input.
"# khushi_task_ds" 
