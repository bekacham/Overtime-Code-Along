# Overtime App

## Real world code along

## Key requirement: company needs documentation that salaried employees did or did not get overtime each week

- x Post -> date:date rationale:text
- x User -> Devise
- x AdminUser -> STI
- x AuditLog

## Features:
- x Approval Workflow
- x SMS Sending -> link to approval or overtime input -> integrate with Heroku scheduler
- x Administrate admin dashboard
- x Block non admin and guest users
- * Email sumary to managers for approval * not working
- x Needs to be documented if employee did not log overtime
- x Create audit log for each text
- x Need to update end_date when confirmed
- x Need to update audit log status when overtime rejected
- x Update buttons on employee homepage so they show on mobile
- x Update buttons to include time span
- x Update button sort order on employee homepage
- x Remove unnecessary nav bar buttons for admins
- x Fix admin dashboard bug
- Implement honeybager error reporting
- Implement new relic for keeping site alive

## TODOS:
