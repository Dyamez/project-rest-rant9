# project-rest-rant Part 9
Part 9: Seeding data, validations, and helper methods
BE class assignment

## In Progress

**CSS** Bootstrap 

**Stack:** MongoDB, Express, NodeJS

**Server-Side Rendering:** JSX

**Node Modules**: method-override, dotenv, express-react-views

## Routes

| Method | Path | Purpose |
| ------ | ------------------------------------- | ----------------------------- |
| GET | `/` | The home page |
| GET | `/places` | Index page listing all places |
| GET | `/places/new` | New form for a place |
| POST | `/places` | Create a new place |
| GET | `/places/:id` | Show one place in detail (Associated rants, new rant form, delete rant button) |
| GET | `/places/:id/edit` | Edit form for a place |
| PUT | `/places/:id` | Make changes to existing place |
| DELETE | `/places/:id` | Delete a place |
| POST | `/places/:id/rant` | Add rant to a place |
| DELETE | `/places/:id/rant/:rantId` | Delete a rant |

## Database

**places** 

| Field | Type |
| ---------- | ------------ |
| _id | Object ID |
| name | String |
| city | String |
| state | String |
| cuisines | String |
| pic | String |

**learning**

| Field | Type |
| ---------- | ------------ |
| _id | Object ID |
| place_id | ref(places) Object_Id |
| rant | Boolean |
| rating | Number |
| comment | String |
| reviewer | String |

### Planning

On Progress

### Introduction

Typing Still...

### Drafting

Paper & Wireframing drafting...

### Ideas
Add-on's
* More Information
* Commenting
* Thumbs-Up or Down
* Dropdown selection