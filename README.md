# Invoice Management System

A comprehensive invoice management system built with pure HTML, CSS, and vanilla JavaScript. No frameworks required!

## Features

- Create, edit, and manage invoices
- Track invoice status (Draft → Sent → In Process → Completed → Logged)
- Multi-user support with sender name tracking
- Real-time updates (polls every 3 seconds)
- Detailed invoice information including:
  - Invoice details with automatic VAT calculations
  - Shipping details
  - Line items with dynamic calculations
  - Payment information
  - Audit trail for logged invoices
- Data persistence using Supabase backend
- Responsive design with Tailwind CSS
- Modal dialogs for detailed invoice viewing

## Technology Stack

- **Frontend**: Pure HTML, CSS, Vanilla JavaScript
- **Styling**: Tailwind CSS (via CDN)
- **Backend**: Supabase Edge Functions
- **Database**: Supabase (PostgreSQL)

## Getting Started

1. Open `index.html` in your browser, or
2. Run with a local server:

```bash
npm install
npm run dev
```

3. Enter your name when prompted
4. Start managing invoices!

## Invoice Workflow

1. **Draft**: Create and save invoices as drafts
2. **Sent**: Send invoices to customers
3. **In Process**: Mark invoices as being processed
4. **Completed**: Mark invoices as completed
5. **Logged**: Approve and log invoices for record keeping

## Features in Detail

### Invoice Creation
- Complete invoice details (company, invoice number, date)
- Shipping information (loading/shipping companies and locations)
- Personnel tracking (operator, sales representative, supplier)
- Dynamic line items with automatic VAT calculation (20%)
- Payment information with automatic calculations
- Multiple calculation sections for different purposes

### Invoice Management
- View all invoices by status
- Edit existing invoices
- Delete unwanted invoices
- Change invoice status with one click
- Track who created, sent, processed, completed, and logged each invoice

### User Experience
- Clean, modern interface
- Responsive design for mobile and desktop
- Real-time data updates
- Modal dialogs for detailed views
- Intuitive tab navigation

## Development

The application uses:
- `localStorage` for sender name persistence
- Fetch API for backend communication
- ES6+ JavaScript features
- CSS Grid and Flexbox for layout
- Custom CSS variables for theming

## License

This project is open source and available for use.
