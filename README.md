# Hotel Management System

A Python-based hotel management system with a Tkinter GUI and Oracle database integration for efficient hotel operations.

## Features

- **Room Allocation**: Automated room assignment based on bed type selection
- **Food & Beverage Management**: Complete menu system with billing
- **Customer Records**: Advanced filtering and database management
- **Billing System**: Automated bill generation with tax calculations
- **Feedback Collection**: Customer rating system with CSV export

## Tech Stack

- **Frontend**: Tkinter (Python GUI)
- **Backend**: Python 3.x
- **Database**: Oracle (cx_Oracle connector)
- **Dependencies**: tkcalendar, datetime, random, math

## Installation

1. **Install dependencies**:
```bash
pip install tkcalendar cx_Oracle
```

2. **Database Setup**:
   - Create Oracle user 'demopython' with password 'himanshu'
   - Create customer table with appropriate schema

## Usage

Run the main application:
```bash
python hotel_management.py
```

## Key Functionalities

- Customer registration with room allocation
- Food ordering with automated billing
- Record filtering by floor, bed type, and dates
- Check-out processing with final billing
- Customer feedback collection

## Database Schema

The system uses a single `customer` table with:
- Name, Phone_Number, Beds, Room_Num, Check_in, Check_out fields

## Room Configuration

- 10 floors with 4 rooms each (40 total rooms)
- Room types: Single (800/day), Double (1500/day), Triple (2000/day)
- Automated availability tracking

## License

Open-source project for educational and demonstration purposes.
