Instruction for running this script and experiment.

Place this queue-disc-benchmark.cc in scratch folder.

Commands to run:

./ns3 run "queue-discs-benchmark --bandwidth=10Mbps --queueDiscType=PIE --bql=false" > rtt_pie_nobql.txt
./ns3 run "queue-discs-benchmark --bandwidth=10Mbps --queueDiscType=PIE --bql=true" > rtt_pie_bql.txt

./ns3 run "queue-discs-benchmark --bandwidth=10Mbps --queueDiscType=FqCoDel --bql=false" > rtt_fqcodel_nobql.txt
./ns3 run "queue-discs-benchmark --bandwidth=10Mbps --queueDiscType=FqCoDel --bql=true" > rtt_fqcodel_bql.txt

./ns3 run "queue-discs-benchmark --bandwidth=10Mbps --queueDiscType=CoDel --bql=false" > rtt_codel_nobql.txt
./ns3 run "queue-discs-benchmark --bandwidth=10Mbps --queueDiscType=CoDel --bql=true" > rtt_codel_bql.txt

./ns3 run "queue-discs-benchmark --bandwidth=10Mbps --queueDiscType=ARED --bql=false" > rtt_ared_nobql.txt
./ns3 run "queue-discs-benchmark --bandwidth=10Mbps --queueDiscType=ARED --bql=true" > rtt_ared_bql.txt

./ns3 run "queue-discs-benchmark --bandwidth=10Mbps --queueDiscType=PfifoFast --bql=false" > rtt_pfifofast_nobql.txt
./ns3 run "queue-discs-benchmark --bandwidth=10Mbps --queueDiscType=PfifoFast --bql=true" > rtt_pfifofast_bql.txt