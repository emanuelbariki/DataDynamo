## DataDynamo Laravel Application

DataDynamo is a system that creates reports from core banking systems. This Laravel application provides a user-friendly interface for creating and managing reports.

### Requirements

* PHP 8.1 or higher
* Laravel 9.x
* MySQL 8.0 or higher

### Installation

1. Clone the repository:

"
git clone https://github.com/your-username/data-dynamo-laravel.git
"

2. Install the dependencies:

"
composer install
"

3. Configure the database:

1. Create a new database for the application.
2. Copy the `.env.example` file to `.env` and update the database credentials.
3. Run the following command to create the database tables:

"
php artisan migrate
"

4. Seed the database:

"
php artisan db:seed
"

5. Start the development server:

"
php artisan serve
"

### Usage

To create a report, simply visit the following URL in your web browser:

"
http://localhost:8000/reports/create
"

You will be prompted to select the type of report you want to create and to enter the relevant parameters. Once you have entered the parameters, click the "Create Report" button to generate the report.

### Contributing

To contribute to this project, please submit your pull requests to the GitHub repository. Please be sure to follow the project's coding style and testing procedures.

### License

This application is licensed under the MIT License.

### Additional Information

For more information about DataDynamo, please see the [DataDynamo website](https://aws.amazon.com/dynamodb/). You can also find support for DataDynamo on the [DataDynamo GitHub repository](https://github.com/DynamoDS/Dynamo).
