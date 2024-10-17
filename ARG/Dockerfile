ARG version
FROM almalinux:${version:-9}
ARG course="Devops" \
    duration="120hrs"  
RUN echo "course: $course, Duration: $duration"   
ENV duration=$duration 
CMD ["sleep", "100"]    
