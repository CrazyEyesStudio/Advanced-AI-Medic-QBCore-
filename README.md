Introducing the Advanced AI Medic – a fully autonomous emergency medical response system. This AI-driven EMS system ensures your players never bleed out alone again!
When EMS is unavailable, a paramedic NPC is dispatched to your location in an ambulance, revives you with a custom animation and prop, and then transports you to the nearest hospital.

Features
:white_check_mark: QBCore support
:rotating_light: /callmedic command triggers AI EMS when no real medics are online
:ambulance: AI Medic drives in an ambulance model
:syringe: Medic revives with animation + medbag prop
:brain: Displays cause of death above the medic in 3D text
:moneybag: Configurable service fee
:hospital: Transports player to nearest configured hospital after revival
:bell: Notifies the player with QBCore Notify or chat fallback
Configuration

Config.MedicModel = 's_m_m_paramedic_01'
Config.AmbulanceModel = 'Ambulance'
Config.ReviveDelay = 10000
Config.Fee = 500
Config.MaxEMSOnline = 5
Config.Hospitals = {
    city = vector3(308.24, -592.42, 43.28),
    sandy = vector3(1828.52, 3673.22, 34.28),
    paleto = vector3(-247.76, 6331.23, 32.43),
    default = vector3(293.0, -582.0, 43.0)
