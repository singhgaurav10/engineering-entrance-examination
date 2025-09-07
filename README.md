# Engineering Entrance Examination Tracker

A comprehensive repository tracking application windows and important dates for major engineering entrance examinations in India. This repository serves as a centralized resource for students, parents, and educational institutions to stay updated with examination schedules and application deadlines.

## Project Overview

### Purpose
This repository maintains structured data about engineering entrance examinations in India, focusing on application windows, important dates, and relevant notes. It helps stakeholders:
- Track application deadlines for multiple examinations
- Plan their application strategy
- Stay informed about updates and corrections
- Access data in multiple formats for analysis

### Target Audience
- Engineering aspirants
- Parents and guardians
- Educational institutions
- Career counselors
- Education researchers
- Data analysts

## Repository Structure

```
engineering-entrance-examination/
├── 2025_batch/
│   ├── EntranceExamData.csv       # Structured CSV data for 2025 examinations
│   ├── EntranceExamTabularData.txt # Data in markdown table format
│   └── EntranceExaminations.txt    # Additional examination information
└── rough_files/
    └── DetailedUnstructuredData.txt # Raw unstructured data
```

### Key Files
1. `EntranceExamData.csv`: Primary data file in CSV format for easy integration with data analysis tools
2. `EntranceExamTabularData.txt`: Data in markdown table format for better readability
3. `DetailedUnstructuredData.txt`: Source data and additional details

## Data Details

### Tracked Examinations
- JEE Main (NTA)
- VITEEE (VIT)
- BITSAT (BITS Pilani)
- KIITEE (KIIT)
- SRMJEEE (SRMIST)
- MET (Manipal/MAHE)
- WBJEE (WBJEEB)
- COMEDK UGET (Karnataka)
- MHT CET (Maharashtra)

### Data Fields
- Exam Name
- Application Start Date
- Application End Date
- Important Notes (corrections, extensions, etc.)

### Data Update Frequency
- Data is updated as official announcements are made
- Each academic year has its own directory (e.g., `2025_batch`)
- Changes are tracked through Git version control

## Usage Instructions

### Accessing Data
1. **CSV Format**: Use `EntranceExamData.csv` for data analysis
   ```python
   # Python/Pandas example
   import pandas as pd
   df = pd.read_csv('2025_batch/EntranceExamData.csv')
   ```
   
2. **Spark Integration**:
   ```python
   # PySpark example
   df = spark.read.csv("EntranceExamData.csv", header=True, quote='"', escape='"')
   ```

3. **Human-Readable Format**: Check `EntranceExamTabularData.txt` for markdown table format

### Data Processing Examples
- Filter examinations by date range
- Track application deadlines
- Analyze examination patterns
- Generate reports and summaries

## Contributing Guidelines

### How to Contribute
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Branch Naming Convention
- Feature branches: `feature/YourFeatureName`
- Bug fixes: `fix/IssueName`
- Documentation: `docs/ChangeName`

### Reporting Issues
- Use the GitHub Issues tab
- Provide clear description of the problem
- Include relevant data and context
- Label issues appropriately

## License

This project is maintained for educational purposes. Please check individual examination websites for official dates and announcements.

## Contact

For questions, suggestions, or collaboration, please:
1. Open an issue
2. Start a discussion
3. Submit a pull request
