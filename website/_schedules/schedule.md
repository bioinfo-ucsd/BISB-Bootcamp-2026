---
timeline:
  - '9:30 AM'
  - '10:00 AM'
  - '10:30 AM'
  - '11:00 AM'
  - '11:30 AM'
  - '12:00 PM'
  - '12:30 PM'
  - '1:00 PM'
  - '1:30 PM'
  - '2:00 PM'
  - '2:30 PM'
  - '3:00 PM'
  - '3:30 PM'
  - '4:00 PM'
  - '4:30 PM'
  - '5:00 PM'
  - '5:30 PM'
types:
  - id: mod
    name: Module 
  - id: program
    name: Program Information
  - id: social
    name: Social Event
  - id: break
    name: Break
  - id: other
    name: Other
schedule:
  - name: Monday
    date: '2026-09-14'
    events:
      - name: Opening Remarks
        type: program
        location: RM 145
        start: "9:30 AM"
        end: "10:30 AM"
        instructors: ["Terry Gaasterland, *BISB Program Chair*"]
        description: "Welcome to the BISB/BMI graduate program! Our program directors will provide an overview of the Bioinformatics and Systems Biology graduate program."
      - name: BISB Administrative Overview
        type: program
        location: RM 145
        start: "10:30 AM"
        end: "11:30 AM"
        instructors: ["Glenn + Amber"]
      - name: "UAW Union Presentation"
        fullname: "UAW Union Presentation"
        type: program
        location: RM 145
        start: "11:30 AM"
        end: "12:00 PM"
      - name: Lunch
        type: break
        start: '12:00 PM'
        end: '1:00 PM'
      - name: "Ice Breakers"
        fullname: "Ice Breakers"
        type: social
        location: RM 145
        start: '1:00 PM'
        end: '2:00 PM'
      - name: "Choose an Advisor/Rotations"
        fullname: "Choose an Advisor/Rotations"
        type: program
        location: RM 145
        start: '2:00 PM'
        end: '2:30 PM'
      - name: "How to Get Paid"
        fullname: "How to Get Paid?"
        type: program
        location: RM 145
        start: '2:30 PM'
        end: '3:00 PM'
      - name: "Course Recommendations"
        fullname: "Course Recommendations"
        type: program
        location: RM 145
        start: '3:00 PM'
        end: '3:30 PM'
      - name: "International Student breakout"
        type: program
        location: RM 145
        start: '3:30 PM'
        end: '4:30 PM'
        
  - name: Tuesday
    date: '2026-09-15'
    events:
      - name: DBMI Introduction
        type: program
        start: '9:30 AM'
        end: '10:00 AM'
        location: RM 145
        instructors: ['Amy Sitapati, *DBMI Director*']
        description: 'For our BMI students, welcome! Dr. Amy Sitapati will introduce the Department of Biomedical Informatics (DBMI) at UCSD. Researchers from BISB and BMI often get to work together so this is a great opportunity for both BISB and BMI students to learn more about the DBMI.'
      - name: "Module 1: Introduction to Statistics"
        type: mod
        location: RM 145
        start: '10:00 AM'
        end: '11:00 AM'
      - name: "Module 2: Introduction to Machine Learning"
        type: mod
        location: RM 145
        start: '11:00 AM'
        end: '12:00 PM'
      - name: "Lunch"
        type: break
        start: '12:00 PM'
        end: '1:00 PM'
      - name: "Predoctoral Fellowships"
        type: program
        location: RM 145
        start: '1:00 PM'
        end: '2:00 PM'
      - name: "Module 3: Paired Programing"
        type: mod
        location: RM 145
        start: '2:00 PM'
        end: '3:30 PM'
      - name: "BISB Guide to San Diego"
        type: social
        location: RM 145
        start: '3:30 PM'
        end: '5:00 PM'

  - name: Wednesday
    date: '2026-09-16'
    events:
      - name: "Mental Health"
        type: other
        location: RM 145
        start: '9:30 AM'
        end: '10:00 AM'
      - name: "Module 4: Virtual Environments"
        location: RM 145
        type: mod
        start: '10:00 AM'
        end: '11:00 AM'
      - name: "Module 5: Software on a team"
        location: RM 145
        type: mod
        start: '11:00 AM'
        end: '12:00 PM'
      - name: Lunch
        type: break
        start: '12:00 PM'
        end: '1:00 PM'
      - name: "Break for walk"
        type: break
        start: '1:00 PM'
        end: '1:30 PM'
      - name: Ropes Course Activity
        type: social 
        start: '1:30 PM'
        end: '5:30 PM'
        location: UCSD Challenge Course (Eucalyptus Grove)
        description: Read about [the course](https://recreation.ucsd.edu/adventures/challenge-course/)!

  - name: Thursday 
    date: '2026-09-17'
    events:
      - name: "Formulating a Scientific Question"
        type: other
        location: RM 145
        start: '9:30 AM'
        end: '10:00 AM'
      - name: "Module 6: Data Science (plotting/pandas)"
        location: RM 145
        type: mod
        start: '10:00 AM'
        end: '11:00 AM'
      - name: "Module 7: Data Science (AI/agents)"
        location: RM 145
        type: mod
        start: '11:00 AM'
        end: '12:00 PM'
      - name: Lunch
        type: break
        start: '12:00 PM'
        end: '1:00 PM'
      - name: "Module 8: PhD Level Scientific Communication"
        type: mod
        location: RM 145
        start: '1:00 PM'
        end: '2:00 PM'
      - name: "Module 9: Introduction to NGS/Benchwork"
        type: mod
        location: RM 145
        start: '2:00 PM'
        end: '3:00 PM'
      - name: "BISB community - Wellness/Diversity"
        type: other
        location: RM 145
        start: '3:00 PM'
        end: '3:30 PM'
      - name: "Module 10: nextflow + snakemake?"
        type: mod
        location: RM 145
        start: '3:30 PM'
        end: '4:30 PM'

  - name: Friday
    date: '2026-09-18'
    events:
      - name: "Module 11: Reproducible Bioinformatics"
        location: MET Upper Auditorium
        type: mod
        start: '10:00 AM'
        end: '11:00 AM'
      - name: "GBIC Reps"
        type: program
        location: MET Upper Auditorium
        start: "11:00 AM"
        end: "11:30 AM"
      - name: "Exit Survey"
        type: program
        location: MET Upper Auditorium
        start: '11:30 AM'
        end: '12:00 PM'
      - name: "Lunch"
        type: break
        start: '12:00 PM'
        end: '1:00 PM'
      - name: "Break for people to walk back/drive"
        fullname: "Break for people to walk back/drive - Avery will coordinate with Sanford staff"
        type: break
        start: '1:00 PM'
        end: '2:30 PM'
      - name: "Welcome Event @Sanford Consortium"
        type: social
        location: Sanford Consortium
        start: '2:30 PM'
        end: '5:30 PM'
---
