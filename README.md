# todo-app-testing-final-assignment
Test report and automation for Todo App based on user stories and performance requirements

Original file line number	Original file line	Diff line number	Diff line change
@@ -0,0 +1,16 @@
todo-app-testing-assignment/
├── test_cases/
│   └── user_stories/          # Individual test cases per user story
├── test_scripts/
│   ├── api/                   # Postman collection/Newman scripts
│   ├── performance/           # k6 or JMeter load tests
│   └── cleanup/               # Database cleanup scripts
├── reports/                   # Generated test reports
├── docs/                      # Report template/documentation
├── config/
│   ├── environment/           # Environment configurations
│   └── database/             # DB connection setup
├── .github/workflows          # CI/CD pipelines
├── .gitignore
├── README.md
└── LICENSE
