# Installation and Setup — English

[English](installation-en.md) | [Deutsch](installation-de.md) | [Home](README.md)

## Install

1. Purchase Ride Dashboard in the Garmin Connect IQ Store.
2. Install it on the Edge 1040 or Edge 1040 Solar and complete the device sync.
3. On the Edge, open the activity profile in which the field should appear.
4. Open its data-screen settings and select a full-width or half-width field.
5. Choose the Connect IQ data-field category, then select `Ride Dashboard`.

Garmin menu names can vary slightly by firmware and device language.

## Configure

Open the Connect IQ settings for Ride Dashboard on the Edge. The overview shows
sample values rather than live ride data. Tap a sample tile to choose its
metric, set the maximum tile count, load the General, Power, or Climbing
preset, or open the display settings.

Values and their units are vertically centered together within each tile.
The `kcal` unit is stacked as `kc` above `al`. Value size always adapts
automatically. When zone colors are enabled, current heart-rate and power zones
are communicated by background color only.

The optional additional strip can show route progress, the current heart-rate
or power zone, or the heart-rate zone-time distribution for the current lap.
Its position can be set to Top or Bottom. If the data required for the selected
strip is unavailable, the strip is hidden and the tiles regain its space.

Ride Dashboard is one app with one shared configuration. Assigning it to a
second data-field area does not create independent settings. All placements use
the same tile order, maximum tile count, and display settings. Compact areas may
show fewer trailing tiles so that the visible values remain legible.

## Required data

- Start an active route for destination, next-point, off-course, and arrival values.
- Configure the rider profile for W/kg, FTP percentage, and heart-rate zones.
- Pair compatible sensors for heart rate, cadence, and power values.
- Pair compatible electronic shifting for gear values.
- Use an Edge 1040 Solar for solar intensity.

`-` means that the selected value is currently unavailable. Check the route,
profile, sensor connection, shifting connection, or device model named in the
metric subtitle.

Affected heart-rate, cadence, power, and electronic-shifting tiles can
alternate between a red warning state and their normal appearance while their
monitored source is missing. The warning starts immediately if that source has
not supplied data in the current session, or after five continuous seconds
without data once it has. A valid value ends the warning immediately. Garmin
may continue to provide an old unchanged value, which Ride Dashboard cannot
distinguish from a live but steady reading.

Ride Dashboard follows the device language when it is one of the 14 supported
languages. Otherwise, it uses English.
