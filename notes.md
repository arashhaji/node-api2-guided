Don't

- Get /list-routines
- Post /new-routine, /create-routine, /routines/new

Do

- Get /routines
- Post /routines

- everthing is resource
- resources live at a URI/L
- operations on those resources are expressed using HTTP methods
- hypermedia (HATEOAS) => links

## Exercise Journal

- view list of `journals`
- view a list of `exercises`
- view a list of `users` to follow
- register for an `account`
- login/logout
- update my profile
- update my profile
- view a user's puplic `profile` 
- view a user's puplic profile
- view the sets for a workout
- view the exercises for a workout 
- view (Get) all workouts that include pushups => filter

https://www.google.com/search
? <= the beginning of the query string
q = rest+api
&
rlz = 1C5CHFA_enUS885DO886
&
oq = Rest+Api
&
aqs = crome.0.0l8.6503j0j8
&
sourceid = chrome
&
ie = 8
&
active = true

```js
req.query = {
    q: "rest api"
    rlz: "1C5CHFA_enUS885DO886"
    ie: "8"
    active: "tru",
}
```


20 resources x 5 => 100 endpoints.

## Resources

- account/users => `/api/users`
- exercises => `/api/exercises`
     - create => Post `/api/exercises`
     - details => Get `/api/exercises
- routines => `/api/routines`
- workouts: a group of sets => `/api/workouts`
     - sets => /api/workouts/:id/set
     - exercises => /api/workeouts/:id/execises
- splits
- sets: have reps => exersise
- muscle groups
- profiles <- same as account?

Monday Workout




