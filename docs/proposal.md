## Classification Project Proposal

The purpose of this project would be to help a company reduce the cost and time invested into of candidates which are likely to seek employment elsewhere after they would have gone through initial training and onboarding.

### Question/need:
What is the purpose of the model/system you plan to build? 
    - To help HR departments understand the factors that lead a person to leave their current job.

### Data:
What dataset(s) do you plan to use, and how will you obtain the data?
 - [Kaggle](https://www.kaggle.com/arashnic/hr-analytics-job-change-of-data-scientists)

What is an individual sample/unit of analysis in this project? What characteristics/features do you expect to work with?

    Features
        enrollee_id : Unique ID for candidate
        city: City code
        city_development_index : Developement index of the city (scaled)
        gender: Gender of candidate
        relevent_experience: Relevant experience of candidate
        enrolled_university: Type of University course enrolled if any
        education_level: Education level of candidate
        major_discipline :Education major discipline of candidate
        experience: Candidate total experience in years
        company_size: No of employees in current employer's company
        company_type : Type of current employer
        lastnewjob: Difference in years between previous job and current job
        training_hours: training hours completed

    Target
        target
            0 – Not looking for job change
            1 – Looking for a job change

### Tools:
How do you intend to meet the tools requirement of the project? 
 - sklearn