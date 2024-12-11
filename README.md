# Organo

Organo is a web application designed to create and manage organizational charts (organograms). It allows users to categorize employees into different teams, mark favorite members, and modify team colors. Users can add new teams, employees, and delete or modify existing ones.

## Features

- **Create Teams**: You can create new teams for your organization and assign specific colors to each team.
- **Add Employees**: Employees can be added to teams with their respective roles and images.
- **Favorite Employees**: Mark employees as favorites to easily highlight key members of the organization.
- **Customize Teams**: Change the color of teams to match your organization's branding.
- **Delete Employees**: Remove employees from the organization if needed.
  
## Tech Stack

- **React**: Front-end framework for building the user interface.
- **UUID**: Used to generate unique IDs for each team and employee.
- **useState**: React hook to manage state for teams and employees.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/organo.git
   ```

2. Install dependencies:
   ```bash
   cd organo
   npm install
   ```

3. Start the application:
   ```bash
   npm start
   ```

This will run the application on [http://localhost:3000](http://localhost:3000).

## Usage

1. **Create a new Team**:
   - Enter the team name and color in the form and click "Create Team."
   
2. **Add Employees**:
   - Select a team from the list, provide employee details (name, role, image), and click "Add Employee."
   
3. **Modify Team Color**:
   - Click on a team to change its color.

4. **Favorite Employees**:
   - Click the heart icon next to an employee's name to mark them as a favorite.

5. **Delete Employees**:
   - Click the trash can icon next to an employee to remove them.

## Components

- **Banner**: Displays the header of the application.
- **Formulario**: Form for adding new employees and teams.
- **Rodape**: Footer of the application.
- **Time**: Represents a team, with its employees and options to modify or delete them.

## Contribution

Feel free to fork the repository and submit pull requests. If you have any issues or suggestions, please open an issue in the repository.
