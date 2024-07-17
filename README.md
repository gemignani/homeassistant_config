Home Assistant Configuration

This repository contains my Home Assistant configuration files. The configuration is organized in a modular structure to enhance readability and maintainability. Below is a summary of the directory structure and its contents.
Directory Structure

    ui-lovelace.yaml: Configuration for the Lovelace UI.
    ui-energy.yaml: Configuration for the Energy Dashboard.
    includes/: Directory containing various configuration components.
        infra/: Infrastructure-related configurations.
            binary_sensors.yaml: Binary sensors configuration.
            input_boolean.yaml: Input boolean entities.
            input_number.yaml: Input number entities.
            input_select.yaml: Input select entities.
            meter.yaml: Meter entities configuration.
            alerts.yaml: Alert notifications.
            alarm_panel.yaml: Alarm panel configuration.
            homeassistant.yaml: General Home Assistant configuration.
        zone/: Zone-related configurations.
            zone.yaml: Definition of zones.
        group/: Group-related configurations.
            xioami.yaml: Xiaomi device groups.
        automations/: Automation scripts.
            kitchen.yaml: Automations for the kitchen.
            system_modes.yaml: System mode automations.
            hall.yaml: Automations for the hall.
            system_heating.yaml: Heating system automations.
            bedroom.yaml: Automations for the bedroom.
            office.yaml: Automations for the office.
            system_alarm.yaml: Alarm system automations.
            lounge.yaml: Automations for the lounge.
            bathroom.yaml: Automations for the bathroom.
            shower.yaml: Automations for the shower.
        sensors/: Sensor configurations.
            sensors_mqtt.yaml: MQTT sensors configuration.
            sensors_statistics.yaml: Statistics sensors configuration.
        local/: Local service configurations.
            notify.yaml: Notification services.
            switch.yaml: Switch entities configuration.
            mqtt.yaml: MQTT configurations.
    scenes.yaml: Configuration for scenes.
    configuration.yaml: Main configuration file for Home Assistant.
