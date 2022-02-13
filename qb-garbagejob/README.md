# Garbage Job V2 For QB-Core

# Changes
- Changed 3D text into Third-eye reality

# Qb-Target config
- Under Config.Peds add the following code to get the garbage man!
```
["garbageman"] = {
    model = 's_m_y_garbage',
    coords = vector4(-322.25, -1545.84, 31.02, 273.78),
    minusOne = true,
    freeze = true,
    invincible = true,
    target = {
        options = {
            {
                type = "client",
                event = "getGarbagePaySlip",
                icon = "far fa-money-bill-wave",
                label = "Collect Paycheck"
            },
            {
                type = "client",
                event = "GarbageTruckSpawn",
                icon = "far fa-truck-moving",
                label = "Spawn Garbage-Truck"
            },
        },
        distance = 2.5,
    },
    currentpednumber = 0,
}
```

# Showcase
- https://streamable.com/6md8or

# Rework Update
- Job now pays per bag delivered on a configured scale.
- Job Randomises the amount of stops and what stops the user goes to
- Job traks rewards on the server rather than client
- Optional Cryptostick find per stop
- Highly Configurable.

# License

    QBCore Framework
    Copyright (C) 2021 Joshua Eger

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>
