# Overview

This is a fully operational Portuguese-language web application featuring a control panel interface ("Painel de Controle") for managing courses and students. The project is an educational management system with a responsive Bootstrap-based frontend, currently running on port 5000. The application includes navigation for courses ("Cursos"), students ("Alunos"), and reports ("Relatórios"), along with a carousel component for featured content with course images.

# User Preferences

Preferred communication style: Simple, everyday language.

# System Architecture

## Frontend Architecture
- **Technology Stack**: Pure HTML5, CSS3, and vanilla JavaScript
- **UI Framework**: Bootstrap 5.3.3 for responsive design and components
- **Layout Pattern**: Fixed navigation header with collapsible off-canvas sidebar menu
- **Responsive Design**: Mobile-first approach using Bootstrap's grid system and responsive utilities

## Component Structure
- **Navigation**: Fixed top navbar with brand logo and primary navigation links
- **Sidebar Menu**: Off-canvas sidebar for secondary navigation (Cursos, Alunos, Relatórios)
- **Main Content**: Container-based layout with carousel component for featured content
- **Interactive Elements**: Bootstrap carousel with indicators for content showcase

## Code Organization
- **Separation of Concerns**: HTML structure, custom CSS styling, and JavaScript functionality are kept in separate files
- **Custom Styling**: Local style.css file with custom color palette (#6492FF, #6663FF, #BACFFF)
- **Static Assets**: Local course images and minimal asset management

## Design Patterns
- **Progressive Enhancement**: Core functionality works without JavaScript, enhanced with Bootstrap components
- **Mobile-First**: Responsive design that adapts from mobile to desktop viewports
- **Component-Based UI**: Modular Bootstrap components for consistent user experience

# External Dependencies

## Frontend Libraries
- **Bootstrap 5.3.3**: Complete UI framework loaded via CDN for styling, responsive grid, and interactive components
- **Bootstrap JavaScript**: For carousel functionality, off-canvas navigation, and responsive behaviors

## CDN Services
- **jsDelivr CDN**: Primary source for Bootstrap CSS and JavaScript files
- **External Hosting**: All framework dependencies are externally hosted, reducing local asset management

## Browser APIs
- **Prompt API**: Used in the utility script for user input collection
- **Alert API**: For displaying calculation results to users