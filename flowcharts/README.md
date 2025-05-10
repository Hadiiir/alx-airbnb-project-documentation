# Airbnb Clone - Process Flowcharts

## Property Booking Workflow
![Booking Process Diagram](booking-process.png)

## Flow Description
1. **Initiation**:
   - User searches available properties
   - Selects desired dates

2. **Validation**:
   - System checks property availability
   - Returns available/unavailable status

3. **Payment Processing**:
   - User enters payment details
   - System verifies payment with processor

4. **Confirmation**:
   - Booking record created
   - Notifications sent to both parties

## Key Decision Points
- Availability check (fail = prompt new search)
- Payment verification (fail = show error)