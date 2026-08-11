<script>
    import { goto } from "$app/navigation";
    import { Folder, FilePlusCorner, MonitorSmartphone } from "lucide-svelte";
</script>

<div class="flex flex-col space-y-2">
    <button class="btn bg-violet-600 border-violet-600" onclick={() => goto("/create")}>
        Create Project
        <FilePlusCorner /></button
    >
    <button
        class="btn btn-outline border-violet-600 text-violet-600 hover:bg-transparent"
        onclick={() => goto(`/edit?id=$`)}
    >
        Open Project
        <Folder /></button
    >

    <button
        class="btn btn-outline border-violet-600 text-violet-600 hover:bg-transparent"
        onclick={() => goto(`/devices`)}
    >
        Connect Devices
        <MonitorSmartphone /></button
    >
</div>
