# Front-End Boilerplate
###Current version: 0.1  

This is a bare bones front-end file structure with boiler plate resets & SASS setup

### Css Naming Conventions

#### Default css for project

[base]
[base] + [modifier] + [modifier]

eg. btn small, text color blue

#### Vendor specific css

[prefix]-[base]
[prefix]-[base] + [modifier]

eg. kr-btn large

So, built in sass:

.btn {
    &.large {
        font-size: 2em;
    }
}
