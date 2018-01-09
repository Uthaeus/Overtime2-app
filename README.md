# Overtime App

## Key requirement: company needs documentation that salaried employees did or did not get overtime each week

## Models
- x Post -> date:date rationale:text
- x User -> Devise
- x AdminUser -> STI

## Features
- Approval Workflow
- SMS Sending -> link to approval or overtime input
- x Administrate admin dashboard
- Email summary to managers for approval
- Needs to be documented if employee did not log overtime
- x Block non admin and guest users

## UI
- x Bootstrap -> formatting
- Icons from Font Awesome
- x Update styles for Forms

## Refactor TODOS
- Refactor user association test in post_spec