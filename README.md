# DataWorks & MaxCompute Practice Project

A hands-on learning repository for Alibaba Cloud DataWorks and MaxCompute with realistic sample data and ETL workflows.

## Project Structure

```
├── data/                     # Sample datasets
├── sql/                      # MaxCompute SQL scripts
├── workflows/                # DataWorks workflow definitions
├── udf/                      # User Defined Functions
├── docs/                     # Documentation and guides
└── scripts/                  # Utility scripts
```

## Getting Started

1. **Prerequisites**
   - Alibaba Cloud account with DataWorks and MaxCompute enabled
   - Basic SQL knowledge
   - Access to DataWorks console

2. **Setup Steps**
   - Create MaxCompute project in your Alibaba Cloud console
   - Create DataWorks workspace and link to MaxCompute project
   - Upload sample data from `/data` folder
   - Run SQL scripts in sequence from `/sql` folder

## Sample Datasets

### E-commerce Data
- **customers.csv**: Customer master data (10K records)
- **products.csv**: Product catalog (1K products)
- **orders.csv**: Order transactions (50K orders)
- **order_items.csv**: Order line items (150K items)

### Web Analytics Data
- **web_sessions.csv**: User session data (100K sessions)
- **page_views.csv**: Page view events (500K events)
- **user_events.csv**: Custom events tracking (200K events)

## Learning Modules

### Module 1: Basic Operations
- Table creation and data loading
- Simple queries and aggregations
- Basic data transformations

### Module 2: ETL Workflows
- Multi-table joins and complex queries
- Data quality checks
- Incremental data processing

### Module 3: Advanced Features
- User Defined Functions (UDFs)
- Window functions and analytics
- Performance optimization

### Module 4: DataWorks Integration
- Workflow orchestration
- Data synchronization
- Scheduling and monitoring

## Practice Exercises

Each module includes practical exercises with expected outputs. Start with Module 1 and progress sequentially.

## Support

- Check `/docs` folder for detailed guides
- Review SQL comments for explanations
- Open issues for questions or improvements

## Contributing

Feel free to add more sample data, SQL scripts, or documentation improvements via pull requests.