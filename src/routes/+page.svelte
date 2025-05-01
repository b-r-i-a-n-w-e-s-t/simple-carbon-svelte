<script lang="ts">
    import { Card, CardGrid } from '@txstate-mws/carbon-svelte'
		import {Button} from 'carbon-components-svelte'
    import { Play, Download, Settings, Search, Send } from 'carbon-icons-svelte'
  </script>

	<Button kind="ghost" icon={Download}>Ghost Button</Button>

  <CardGrid>
    <Card
      title="Project Dashboard"
      subhead="Status: In Progress"
      actions={ [{ label: 'Export', icon: Download }, { label: 'Settings', icon: Settings }] }
      tags={ [{ label: 'High Priority' }, { label: 'Team Collaboration' }] }
      navigations={ [{ label: 'View Details', href: '#'}, { label: 'Edit Project', href: '#'}] }
    >
      Project milestones and deliverables are on track. Team collaboration metrics show strong engagement.
    </Card>

    <Card
      title="Task Management"
      subhead="24 active tasks"
      actions={ [{ label: 'Add Task', icon: Play }] }
      tags={ [{ label: 'Task Board' }, { label: 'Time Tracking' }] }
      navigations={ [{ label: 'View All Tasks', href: '#'}, { label: 'Assign Tasks', href: '#'}] }
    >
      Manage your team's tasks and track progress with our intuitive task board.
    </Card>

    <Card
      title="Team Performance"
      subhead="Q3 2024"
      actions={ [{ label: 'Export Data', icon: Download }] }
      tags={ [{ label: 'Analytics' }, { label: 'Metrics' }] }
      navigations={ [{ label: 'View Dashboard', href: '#'}, { label: 'Custom Reports', href: '#'}] }
    >
      Analyze team performance metrics and identify areas for improvement.
    </Card>

    <Card
      title="Resource Planning"
      subhead="Capacity Analysis"
      actions={ [{ label: 'Update Schedule', icon: Settings }] }
      tags={ [{ label: 'Resource Allocation' }, { label: 'Scheduling' }] }
      navigations={ [{ label: 'View Calendar', href: '#'}, { label: 'Adjust Resources', href: '#'}] }
    >
      Optimize resource allocation and ensure project timelines are met.
    </Card>

    <Card
      title="Client Feedback"
      subhead="Latest Reviews"
      actions={ [{ label: 'Send Survey', icon: Send }, { label: 'Search', icon: Search }] }
      tags={ [{ label: 'Customer Success' }, { label: 'Feedback Loop' }] }
      navigations={ [{ label: 'View Analytics', href: '#'}, { label: 'Manage Feedback', href: '#'}] }
    >
      Gather and analyze client feedback to improve service delivery.
    </Card>
  </CardGrid>
